# �\���֐����C�u����

���̃��C�u�������g���ɂ̓\�[�X�R�[�h��
```
include "Print.mok";
```
�ƒǉ����܂��B

## �⏕�֐�
### bracket�֐�
```
bracket : (() -> ()) -> ()
```
�֐��̎��s�̑O��Ɋp���ʂ��o�͂���

### paren�֐�
```
paren : (() -> ()) -> ()
```
�֐��̎��s�̑O��Ɋ��ʂ��o�͂���

### endl�֐�
```
endl : (() -> ()) -> ()
```
�֐������s���ĉ��s�������o�͂���B

### sep�֐�
```
sep : �� -> (�� -> ()) -> [��] -> ()
```
`sep x f lis`��`lis`�̊e�v�f�Ɋ֐�`f`��K�p���A
���̊Ԃ�`x`���o�͂���B

## ���X�g�̕\��

### print_list_with
```
print_list_with : (�� -> ()) -> [��] -> ()
```
�w�肵���֐����g���ă��X�g�̗v�f��\������B

### println_list_with
```
println_list_with : (�� -> ()) -> [��] -> ()
```
���X�g�̊e�v�f��\�����ĉ��s����B

### print_list
```
print_list : [��] -> ()
```
���X�g��\������B

### println_list
```
println_list : [��] -> ()
```
���X�g��\�����ĉ��s����B

## 2�v�f�^�v���̕\��
### print_tuple2_with
```
print_tuple2_with : (�� -> (), �� -> ()) -> (��, ��) -> ()
print_pair_with : (�� -> (), �� -> ()) -> (��, ��) -> ()
```
�w�肵���֐����g���ă^�v����\������B

### println_tuple2_with
```
println_tuple2_with : (�� -> (), �� -> ()) -> (��, ��) -> ()
println_pair_with : (�� -> (), �� -> ()) -> (��, ��) -> ()
```
�w�肵���֐����g���ă^�v����\�����ĉ��s����B

### print_tuple2
```
print_tuple2 : (��, ��) -> ()
print_pair : (��, ��) -> ()
```
�^�v����\������B

### println_tuple2
```
println_tuple2 : (��, ��) -> ()
println_pair : (��, ��) -> ()
```
�^�v����\�����ĉ��s����B

## 3�v�f�^�v���̕\��
### print_tuple3_with
```
print_tuple3_with : (�� -> (), �� -> (), �� -> ()) -> (��, ��, ��) -> ()
```
�w�肵���֐����g���ă^�v����\������B

### println_tuple3_with
```
println_tuple3_with : (�� -> (), �� -> (), �� -> ()) -> (��, ��, ��) -> ()
```
�w�肵���֐����g���ă^�v����\�����ĉ��s����B

### print_tuple3
```
print_tuple3 : (��, ��, ��) -> ()
```
�^�v����\������B

### println_tuple3
```
println_tuple3 : (��, ��, ��) -> ()
```
�^�v����\�����ĉ��s����B

## 4�v�f�^�v���̕\��
### print_tuple4_with
```
print_tuple4_with : (�� -> (), �� -> (), �� -> (), �� -> ()) -> (��, ��, ��, ��) -> ()
```
�w�肵���֐����g���ă^�v����\������B

### println_tuple4_with
```
println_tuple4_with : (�� -> (), �� -> (), �� -> (), �� -> ()) -> (��, ��, ��, ��) -> ()
```
�w�肵���֐����g���ă^�v����\�����ĉ��s����B

### print_tuple4
```
print_tuple4 : (��, ��, ��, ��) -> ()
```
�^�v����\������B

### println_tuple4
```
println_tuple4 : (��, ��, ��, ��) -> ()
```
�^�v����\�����ĉ��s����B