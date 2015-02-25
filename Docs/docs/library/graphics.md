# �O���t�B�b�N�X���C�u����

���̃��C�u�������g���ɂ̓\�[�X�R�[�h��
```
include "Graphics.mok";
```
�ƒǉ����܂��B

## MouseButton
```
type MouseButton =
    LeftButton
  | RightButton
  | MiddleButton
  | UnknownButton;
```

## Event
```
type Event =
    Draw({Graphics})
  | Tick
  | MouseDown(MouseButton, Int, Int)
  | MouseMove(Int, Int)
  | MouseUp(MouseButton, Int, Int);
```

## �V�[��
### scene�֐�
```
scene : String -> (Event -> ()) -> ()
```
�V�����V�[�����`����B

### switch�֐�
```
switch : String -> ()
```
�V�[����؂�ւ���B

## �^�C�}�[
### set_speed�֐�
```
set_speed : Int -> ()
```
`Tick`�C�x���g�𔭍s���銴�o���~���b�Ŏw�肷��B

## �E�C���h�E
### show_window�֐�
```
show_window : String -> ()
```
�E�C���h�E��\������B�����͏����V�[�����B

### set_title�֐�
```
set_title : String -> ()
```
�E�C���h�E�̃^�C�g����ݒ肷��B

### set_size�֐�
```
set_size : Int -> Int -> ()
```
�E�C���h�E�̕��ƍ������w�肷��B

### redraw�֐�
```
redraw : () -> ()
```
�E�C���h�E�̓��e���ĕ`�悷��B

## �y��
### new_pen�֐�
```
new_pen : Int -> Int -> Int -> Int -> {System.Drawing.Pen}
```
`newpen r g b w`�ŐF`(r,g,b)`�Ɛ���`w`�̃y�������B

### ����̃y��
```
black_pen : {System.Drawing.Pen}
white_pen : {System.Drawing.Pen}
red_pen : {System.Drawing.Pen}
green_pen : {System.Drawing.Pen}
blue_pen : {System.Drawing.Pen}
yellow_pen : {System.Drawing.Pen}
cyan_pen : {System.Drawing.Pen}
magenta_pen : {System.Drawing.Pen
```

## �u���V
### new_solid_brush
```
new_solid_brush : Int -> Int -> Int -> {System.Drawing.Brush}
```
`new_solid_brush r g b`�ŐF`(r,g,b)`�̃u���V�����B

### ����̃u���V
```
black_brush : {System.Drawing.Brush}
white_brush : {System.Drawing.Brush}
red_brush : {System.Drawing.Brush}
green_brush : {System.Drawing.Brush}
blue_brush : {System.Drawing.Brush}
yellow_brush : {System.Drawing.Brush}
cyan_brush : {System.Drawing.Brush}
magenta_brush : {System.Drawing.Brush}
```

## �`��֐�
### draw_line�֐�
```
draw_line : {System.Drawing.Graphics} -> {System.Drawing.Pen} ->
    Int -> Int -> Int -> Int -> ()
```
`draw_line graphics pen x1 y1 x2 y2`�Ŏw�肵�����W�Ԃɐ��������B

### draw_rectangle�֐�
```
draw_rectangle : {System.Drawing.Graphics} -> {System.Drawing.Pen} ->
    Int -> Int -> Int -> Int -> ()
```
`draw_rectangle graphics pen x y w h`�Ŏw�肵���傫���̎l�p�`���A
�w�肵�����W�ɕ`���B

### draw_ellipse�֐�
```
draw_ellipse : {System.Drawing.Graphics} -> {System.Drawing.Pen} ->
    Int -> Int -> Int -> Int -> ()
```
`draw_ellipse graphics pen x y w h`�Ŏw�肵���傫���̎l�p�`��
���ڂ���ȉ~��`���B

### draw_string�֐�
```
draw_string : {System.Drawing.Graphics} -> {System.Drawing.Brush} ->
    �� -> Int -> Int -> Int -> ()
```
`draw_string graphics brush string size x y `�ŕ������`���B

### fill_rectangle�֐�
```
fill_rectangle : {System.Drawing.Graphics} -> {System.Drawing.Brush} ->
    Int -> Int -> Int -> Int -> ()
```
`fill_rectangle graphics brush x y w h`�œh��Ԃ����l�p�`��`���B

### fill_ellipse�֐�
```
fill_ellipse : {System.Drawing.Graphics} -> {System.Drawing.Brush} ->
    Int -> Int -> Int -> Int -> ()
```
`fill_ellipse graphics brush x y w h`�œh��Ԃ����ȉ~��`���B

### draw_pixel�֐�
```
draw_pixel : {System.Drawing.Graphics} ->
   Int -> Int -> Int -> Int -> Int -> ()
```
`draw_pixel graphics r g b x y`�Ŏw�肵�����W�Ɏw�肵���F�̃s�N�Z����łB

## �F�̕ϊ�
### hsv_to_rgb�֐�
```
hsv_to_rgb : Double -> Double -> Double -> (Int, Int, Int)
```
�F��(0.0-360.0)�A�ʓx(0.0-1.0)�A���x(0.0-1.0)��RGB�l�ɕϊ�����B
