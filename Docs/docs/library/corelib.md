# �R�A���C�u����
## �V�X�e���֐�

### println�֐�
```
println : �� -> ()
```
�����A���������_���A������A�����̒l��\�����ĉ��s���܂��B

### print�֐�
```
print : �� -> ()
```
�����A���������_���A������A�����̒l��\�����܂��B

### error�֐�
```
error : String -> ��
```
���s���G���[�𔭐������܂��B
�����ɂ̓G���[���e���L�q���܂��B

### undefined�֐�
```
undefined : �� -> ��
```
�ϐ���֐�������`�ł��邱�Ƃ������܂��B

### ignore�֐�
```
ignore : �� -> ()
```
�����𖳎�����`()`��Ԃ��܂��B

## ��r���Z
### (==)���Z�q
```
__operator_eqeq : �� -> �� -> Bool
```
�����A���������_���A������A�����A�^�U�l�A���j�b�g�̒l���r���A
���������`true`�������łȂ����`false`��Ԃ��܂��B

### (<>)���Z�q
```
__operator_ltgt : �� -> �� -> Bool
```
�����A���������_���A������A�����A�^�U�l�A���j�b�g�̒l���r���A
���������`false`�������łȂ����`true`��Ԃ��܂��B

### (<)���Z�q
```
__operator_lt : �� -> �� -> Bool
```
�����A���������_���A������A�����A�^�U�l�A���j�b�g�̒l���r���A
���ӂ̕����E�ӂ̒l��菬�����ꍇ��`true`���A
�����łȂ��ꍇ��`false`��Ԃ��܂��B

### (>)���Z�q
```
__operator_gt : �� -> �� -> Bool
```
�����A���������_���A������A�����A�^�U�l�A���j�b�g�̒l���r���A
���ӂ̕����E�ӂ̒l���傫���ꍇ��`true`���A
�����łȂ��ꍇ��`false`��Ԃ��܂��B

### (<=)���Z�q
```
__operator_le : �� -> �� -> Bool
```
�����A���������_���A������A�����A�^�U�l�A���j�b�g�̒l���r���A
���ӂ̕����E�ӂ̒l�ȉ��̏ꍇ��`true`���A
�����łȂ��ꍇ��`false`��Ԃ��܂��B

### (>=)���Z�q
```
__operator_le : �� -> �� -> Bool
```
�����A���������_���A������A�����A�^�U�l�A���j�b�g�̒l���r���A
���ӂ̕����E�ӂ̒l�ȏ�̏ꍇ��`true`���A
�����łȂ��ꍇ��`false`��Ԃ��܂��B

### intequal�֐�
```
intequal : Int -> Int -> Bool
```
2�̒l�𐮐��Ƃ��Ĕ�r���āA�������ꍇ��`true`���A
�����łȂ��ꍇ��`false`��Ԃ��܂��B
�񋓑̂̒l�𓙂����𔻒肷��ꍇ�Ɏg���܂��B

### max�֐�
```
max : �� -> �� -> ��
```
2�̈����̂����傫�����̒l��Ԃ��܂��B
�l�́A�����A���������_���A������A�����A�^�U�l�A���j�b�g�̒l��
�����ꂩ�ł���K�v������܂��B

### min�֐�
```
min : �� -> �� -> ��
```
2�̈����̂������������̒l��Ԃ��܂��B
�l�́A�����A���������_���A������A�����A�^�U�l�A���j�b�g�̒l��
�����ꂩ�ł���K�v������܂��B

## �������Z
### (+)���Z�q
```
__operator_pls : Int -> Int -> Int
```
�������m�̉��Z�ł��B

### (-)���Z�q
```
__operator_mns : Int -> Int -> Int
```
�������m�̌��Z�ł��B

### (*)���Z�q
```
__operator_ast : Int -> Int -> Int
```
�������m�̏�Z�ł��B

### (/)���Z�q
```
__operator_sls : Int -> Int -> Int
```
�������m�̏��Z�ł��B

### (%)���Z�q
```
__operator_per : Int -> Int -> Int
```
�������m�̏�]�ł��B

### (~-)���Z�q
```
__operator_neg : Int -> Int
```
�����̕����𔽓]���܂��B

### succ�֐�
```
succ : Int -> Int
```
�����̒l��1�������l��Ԃ��܂��B

### pred�֐�
```
pred : Int -> Int
```
�����̒l����1�������l��Ԃ��܂��B

### abs�֐�
```
abs : Int -> Int
```
�����̐����̐�Βl�����߂܂��B

## �r�b�g���Z
### band�֐�
```
band : Int -> Int -> Int
```
2�̐����̃r�b�g���Ƃ̘_���ς����߂܂��B

### bor�֐�
```
bor : Int -> Int -> Int
```
2�̐����̃r�b�g���Ƃ̘_���a�����߂܂��B

### bxor�֐�
```
bxor : Int -> Int -> Int
```
2�̐����̃r�b�g���Ƃ̔r���I�_���a�����߂܂��B

### bnot�֐�
```
bnot : Int -> Int
```
�����̂��ׂẴr�b�g�𔽓]�����l��Ԃ��܂��B

### bshr�֐�
```
bshr : Int -> Int -> Int
```
�������w�肵���l�������E�ɎZ�p�V�t�g���܂��B

### bshl�֐�
```
bshl : Int -> Int -> Int
```
�������w�肵���l���������ɃV�t�g���܂��B

### bshrun�֐�
```
bshrun : Int -> Int -> Int
```
�������w�肵���l�������E�ɘ_���V�t�g���܂��B

## ���������_�����Z
### (+.)���Z�q
```
__operator_plsdot : Double -> Double -> Double
```
���������_�����m�̘a�����߂܂��B

### (-.)���Z�q
```
__operator_mnsdot : Double -> Double -> Double
```
���������_�����m�̍������߂܂��B

### (*.)���Z�q
```
__operator_astdot : Double -> Double -> Double
```
���������_�����m�̐ς����߂܂��B

### (/.)���Z�q
```
__operator_astdot : Double -> Double -> Double
```
���������_���̍��ӂ̒l���E�ӂ̒l�Ŋ������l�����߂܂��B

### (~-.)���Z�q
```
__operator_negdot : Double -> Double
```
���������_���̕����𔽓]���܂��B

### fabs�֐�
```
fabs : Double -> Double
```

### pi�萔
```
pi : Double
```
�~�����ł��B

### pi2�萔
```
pi2 : Double
```
�~������2�{�ł��B

### e�萔
```
e : Double
```
���R�ΐ��̒�ł��B

### sqrt�֐�
```
sqrt : Double -> Double
```
�����������߂܂��B

### exp�֐�
```
exp : Double -> Double
```
���R�ΐ��̒�̗ݏ�����߂܂��B

### log�֐�
```
log : Double -> Double
```
���R�ΐ��ł��B

### log10�֐�
```
log10 : Double -> Double
```
��p�ΐ��ł��B

### logn�֐�
```
logn : Double -> Double -> Double
```
`logn x base`�őΐ��̒�`base`���w�肵��`x`�̑ΐ������߂܂��B

### pow�֐�
```
pow : Double -> Double -> Double
```
`pow x y`��`x`��`y`������߂܂��B

### sin�֐�, cos�֐�, tan�֐�
```
sin : Double -> Double
cos : Double -> Double
tan : Double -> Double
```
�O�p�֐��ł��B�P�ʂ̓��W�A���ł��B

### asin�֐�, acos�֐�, atan�֐�
```
asin : Double -> Double
acos : Double -> Double
atan : Double -> Double
```
�t�O�p�֐��ł��B

### atan2�֐�
```
atan2 : Double -> Double -> Double
```
`atan2 x y`��`x/y`�̋t���ڂ����߂܂��B

### sinh�֐��Acosh�֐��Atanh�֐�
```
�o�Ȑ��֐��ł��B
```

### ceiling�֐�
```
ceiling : Double -> Double
```
�w�肵�����ȏ�̐��̂����ŏ��̐����l��Ԃ��܂��B

### truncate�֐�
```
truncate : Double -> Double
```
�w�肵�����̐�������Ԃ��܂��B

### round�֐�
```
round : Double -> Double
```
�w�肵�������ł��߂������Ɋۂ߂܂��B

### floor�֐�
```
floor : Double -> Double
```
�w�肵�����ȉ��̐��̂����ő�̐����l��Ԃ��܂��B

## �����񉉎Z
### (^)���Z�q
```
__operator_hat : String -> String -> String
```
2�̕������A�����܂��B

### to_string�֐�
```
to_string : �� -> String
```
�����̒l�𕶎��񉻂��܂��B
�l�́A�����A���������_���A������A�����̂����ꂩ�ł���K�v������܂��B

### strlen�֐�
```
strlen : String -> Int
```
������̒��������߂܂��B

### strnth�֐�
```
strnth : String -> Int -> Char
```
�������n�Ԗڂ̕�����Ԃ��܂��B

## �������Z
```
is_control : Char -> Bool
```
���������䕶���ł���ΐ^��Ԃ��܂��B

```
is_digit : Char -> Bool
```
�������\�i�����ł���ΐ^��Ԃ��܂��B

```
is_letter : Char -> Bool
```
������Unicode�����ł���ΐ^��Ԃ��܂��B

```
is_letter_or_digit : Char -> Bool
```
������Unicode�������\�i�����ł���ΐ^��Ԃ��܂��B

```
is_lower : Char -> Bool
```
�������������ł���ΐ^��Ԃ��܂��B

```
is_symbol : Char -> Bool
```
�������L���ł���ΐ^��Ԃ��܂��B

```
is_upper : Char -> Bool
```
�������啶���ł���ΐ^��Ԃ��܂��B

```
is_whitespace : Char -> Bool
```
�������󔒕����ł���ΐ^��Ԃ��܂��B

```
to_lower : Char -> Char
```
�������������ɕϊ����܂��B

```
to_upper : Char -> Char
```
������啶���ɕϊ����܂��B

## �_�����Z

### not�֐�
```
not : Bool -> Bool
```
�^�U�l�̔��]�ł��B

```
xor : Bool -> Bool -> Bool
```
�^�U�l�̔r���I�_���a�ł��B

## �ϊ�
### parse_int�֐�
```
parse_int : String -> Int
```
������\��������𐮐��l�ɕϊ����܂��B

### parse_double�֐�
```
parse_double : String -> Double
```
���������_����\��������𕂓������_���l�ɕϊ����܂��B

### int_to_double�֐�
```
int_to_double : Int -> Double
```
�����𕂓������_���l�ɕϊ����܂��B

### double_to_int�֐�
```
double_to_int : Double -> Int
```
���������_���l�𐮐��ɕϊ����܂��B

### int_to_char�֐�
```
int_to_char : Int -> Char
```
�����R�[�h�𕶎��ɕϊ����܂��B

### char_to_int�֐�
```
char_to_int : Char -> Int
```
�����̕����R�[�h��Ԃ��܂��B

### int_to_single�֐�
```
int_to_single : Int -> {System.Single}
```
������P���x���������_���ɕϊ����܂��B

### single_to_int�֐�
```
single_to_int : {System.Single} -> Int
```
�P���x���������_���𐮐��ɕϊ����܂��B

### double_to_single�֐�
```
double_to_single : Double -> {System.Single}
```
�{���x���������_����P���x���������_���ɕϊ����܂��B

### single_to_double�֐�
```
single_to_double : {System.Single} -> Double
```
�P���x���������_����{���x���������_���ɕϊ����܂��B

### box�֐�
```
box : �� -> {System.Object}
```
�l��Object�^�ɃL���X�g���܂��B

## �֐�

### (<|)���Z�q
```
__operator_ltbar : (�� -> ��) -> �� -> ��
```
�֐��K�p���Z�q�B

### (|>)���Z�q
```
__operator_bargt : �� -> (�� -> ��) -> ��
```
�t�����֐��K�p���Z�q

### (<<)���Z�q
```
__operator_ltlt : (�� -> ��) -> (�� -> ��) -> �� -> ��
```
�֐������B

### (>>)���Z�q
```
__operator_gtgt : (�� -> ��) -> (�� -> ��) -> �� -> ��
```
�t�����֐������B

### match�֐�
```
match : �� -> (�� -> ��) -> ��
```
��1�����̒l���2�����̊֐��ɓK�p����B

### id�֐�
```
id : �� -> ��
```
�P���֐��B

### const�֐�
```
const : �� -> �� -> ��
```
2�����󂯎���āA1�����ڂ�Ԃ��B

### flip�֐�
```
flip : (�� -> �� -> ��) -> �� -> �� -> ��
```
�֐��̈����������ւ���B

## �^�v��
### fst�֐�
```
fst : (��, ��) -> ��
```
2�v�f�^�v���̍ŏ��̗v�f��Ԃ��B

### snd�֐�
```
snd : (��, ��) -> ��
```
2�v�f�^�v����2�Ԗڂ̗v�f��Ԃ��B

### curry�֐�
```
curry : ((��, ��) -> ��) -> �� -> �� -> ��
```
�֐����J���[������B

### uncurry�֐�
```
uncurry : (�� -> �� -> ��) -> (��, ��) -> ��
```
�֐��̃J���[������������B

## ���t�@�����X�Z��
### ref�֐�
```
ref : �� -> Ref<��>
```
���t�@�����X�Z�������B

### (!)���Z�q
```
__operator_bang : Ref<��> -> ��
```
�Q�Ƃ𔍂����B

### (:=)���Z�q
```
__operator_coleq : Ref<��> -> �� -> ()
```
�Q�Ƃɑ������B

### incr�֐�
```
incr : Ref<Int> -> ()
```
�Q�Ƃ̒l��1���₷�B

### decr�֐�
```
decr : Ref<Int> -> ()
```
�Q�Ƃ̒l��1���炷

## ���X�g
### (..)���Z�q
```
__operator_dotdot : Int -> Int -> [Int]
```
�w�肵���͈͂̐������܂ރ��X�g�𐶐�����B

### (++)���Z�q
```
__operator_plspls : [��] -> [��] -> [��]
```
2�̃��X�g��A������B

### length�֐�
```
length : [��] -> Int
```
���X�g�̒�����Ԃ��B

### reverse�֐�
```
reverse : [��] -> [��]
```
���]�������X�g��Ԃ��B

### map�֐�
```
map : (�� -> ��) -> [��] -> [��]
```
���X�g�̊e�v�f�Ɋ֐���K�p�������X�g��Ԃ��B

### is_nil�֐�
```
is_nil : [��] -> Bool
```
���X�g���󃊃X�g�ł���ΐ^��Ԃ��܂��B

### head�֐�
```
head : [��] -> ��
```
���X�g�̐擪�v�f��Ԃ��B

### tail�֐�
```
tail : [��] -> [��]
```
���X�g�̐擪����菜�������X�g��Ԃ��B

### nth�֐�
```
nth : [��] -> Int -> ��
```
���X�g��n�Ԗڂ̗v�f��Ԃ�

### foldl�֐�
```
foldl : (�� -> �� -> ��) -> �� -> [��] -> ��
```
���X�g��������E�Ɍ������ď�ݍ��݂���B

### foldr�֐�
```
foldr : (�� -> �� -> ��) -> �� -> [��] -> ��
```
���X�g���E���獶�Ɍ������ď�ݍ��݂���B

### lookup�֐�
```
lookup : �� -> [(��, ��)] -> Maybe<��>
```
�A�z���X�g����Ή�����l��T������B
������Ȃ����`Nothing`�����������ꍇ��`Just`�ł���񂾒l��Ԃ��B

### concat�֐�
```
concat : [[��]] -> [��]
```
���X�g�̃��X�g�����X�g�ɕϊ�����B

### concat_map�֐�
```
concat_map : (�� -> [��]) -> [��] -> [��]
```
`map`���Ă��̌��ʂ�`concat`����B
 
## Maybe
```
type Maybe<T> = Nothing | Just(T);
```
### maybe�֐�
```
maybe : �� -> (�� -> ��) -> Maybe<��> -> ��
```
`Maybe`�l�Ɋ֐���K�p����B`Nothing`�̂Ƃ��̓f�t�H���g�l��Ԃ��B

### map_maybe�֐�
```
map_maybe : (�� -> ��) -> Maybe<��> -> Maybe<��>
```
`Maybe`�l�Ɋ֐���K�p����B`Nothing`�̂Ƃ���`Nothing`��Ԃ��B

### is_just�֐�
```
is_just : Maybe<��> -> Bool
```
`Just(_)`�ł����`true`��Ԃ��A�����łȂ����`false`��Ԃ��B

### is_nothing�֐�
```
is_nothing : Maybe<��> -> Bool
```
`Nothing`�ł����`true`��Ԃ��A�����łȂ����`false`��Ԃ��B

### from_just�֐�
```
from_just : Maybe<��> -> ��
```
`Maybe`�l����l�����o���B`Nothing`�̏ꍇ�̓G���[

## �����̃��X�g
### string_to_list
```
string_to_list : String -> [Char]
```
������𕶎��̃��X�g�ɕϊ����܂��B

```
list_to_string : [Char] -> String
```
�����̃��X�g�𕶎���ɕϊ����܂��B

## Either
```
type Either<T, U> = Left(T) | Right(U);
```

### either�֐�
```
either : (�� -> ��) -> (�� -> ��) -> Either<��, ��> -> ��
```
`Either`�l�Ɋ֐���K�p����B

## �z��
### list_to_array�֐�
```
list_to_array : [{System.Object}] -> {System.Object[]}
```
`Object`�̃��X�g��`Object[]`�ɕϊ�����B

### format�֐�
```
format : String -> [{System.Object}] -> String
```
�t�H�[�}�b�g������ɏ]���āA�l�𕶎���ɕϊ�����B

## ���t���N�V����
### get_type�֐�
```
get_type : String -> {System.Type}
```
�w�肵�����O��`Type`�I�u�W�F�N�g��Ԃ��B

### null�萔
```
null : {System.Object}
```
null�l�B

## ���b�Z�[�W
### msgbox�֐�
```
msgbox : �� -> ()
```
���b�Z�[�W�{�b�N�X�ɒl��\������B
�l�͐����A���������_���A������A�����̂����ꂩ�B
