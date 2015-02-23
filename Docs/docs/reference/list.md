# ���X�g���C�u����

## ��{�I�Ȋ֐�

### last
```
last : [��] -> ��
```
���X�g�̍Ō�̗v�f��Ԃ��܂��B

### init
```
init : [��] -> [��]
```
�Ō�̗v�f�����������X�g��Ԃ��܂��B

### is_null
```
is_null : [��] -> Bool
```
���X�g���󂩒��ׂ܂��B

## ���X�g�̓��ʂȏ�ݍ���

### any
```
any : (�� -> Bool) -> [��] -> Bool
```
`any p xs`�Ń��X�g`xs`�̗v�f�̂����ꂩ���q��`p`�𖞂��������ׂ܂��B

### all
```
all : (�� -> Bool) -> [��] -> Bool
```
`all p xs`�Ń��X�g`xs`�̗v�f�̂��ׂĂ��q��`p`�𖞂��������ׂ܂��B

### sum
```
sum : [Int] -> Int
```
�����̃��X�g�̑��a��Ԃ��܂��B

### product
```
product : [Int] -> Int
```
�����̃��X�g�̑����Ԃ��܂��B

### maximum
```
maximum : [��] -> ��
```
�ő�l��Ԃ��܂��B

### minimum
```
minimum : [��] -> ��
```
�ŏ��l��Ԃ��܂��B

## ���X�g�̐���

### replicate
```
replicate : Int -> �� -> [��]
```
`replicate n x`�Œ���`n`�ł��ׂĂ̗v�f��`x`�̃��X�g��Ԃ��܂��B

## �������X�g

### take
```
take : Int -> [��] -> [��]
```
`take n xs`�Ń��X�g`xs`�̐擪����`n`�Ԗڂ܂ł̃��X�g��Ԃ��܂��B

### drop
```
drop : Int -> [��] -> [��]
```
`drop n xs`�Ń��X�g`xs`�̐擪����`n`�Ԗڂ����̃��X�g��Ԃ��܂��B

### split_at
```
split_at : Int -> [��] -> ([��], [��])
```
`split n xs`�Ń��X�g`xs`�̐퓬����`n`�Ԗڂ܂ł̃��X�g�Ƃ�������̃��X�g�̃y�A��Ԃ��܂��B

### take_while
```
take_while : (�� -> Bool) -> [��] -> [��]
```
`take_while p xs`�Ń��X�g`xs`�̐擪����q��`p`�𖞂����͈͂̃��X�g��Ԃ��܂��B

### drop_while
```
drop_while : (�� -> Bool) -> [��] -> [��]
```
`drop_while p xs`�Ń��X�g`xs`�̐擪����q��`p`�𖞂����͈͂����������X�g��Ԃ��܂��B

## ���X�g�̌���

### elem
```
elem : �� -> [��] -> Bool
```
`elem x xs`��`x`�����X�g`xs`�Ɋ܂܂�邩���ׂ܂��B

### not_elem
```
not_elem : �� -> [��] -> Bool
```
`not_elem x xs`��`x`�����X�g`xs`�Ɋ܂܂�Ȃ������ׂ܂��B

### find
```
find : (�� -> Bool) -> [��] -> Maybe<��>
```
`find p xs`�ŏq��`p`�𖞂������X�g`xs`�̍ŏ��̗v�f��Ԃ��܂��B

### filter
```
filter : (�� -> Bool) -> [��] -> [��]
```
`filter p xs`�ŏq��`p`�𖞂������X�g`xs`�̗v�f�����ׂĕԂ��܂��B

### partition
```
partition : (�� -> Bool) -> [��] -> ([��], [��])
```
`partition p xs`�Ń��X�g`xs`�̂����q��`p`�𖞂������̂Ƃ����łȂ����̂̃y�A��Ԃ��܂��B

## ���X�g��zip�֐���unzip�֐�

### zip
```
zip : [��] -> [��] -> [(��, ��)]
```
2�̃��X�g���󂯎��A�y�A�̃��X�g��Ԃ��܂��B

### zip_with
```
zip_with : (�� -> �� -> ��) -> [��] -> [��] -> [��]
```
��ʉ�����zip�֐�

### unzip
```
unzip : [(��, ��)] -> ([��], [��])
```
�y�A�̃��X�g���󂯎��A���X�g�̃y�A��Ԃ��܂��B

## ���X�g�̑���

### iter
```
iter : (�� -> ()) -> [��] -> ()
```
���X�g�̊e�v�f�ɃA�N�V������K�p���܂��B

### iteri
```
iteri : (Int -> �� -> ()) -> [��] -> ()
```
�C���f�b�N�X�t����iter�֐�

### mapi
```
mapi : (Int -> �� -> ��) -> [��] -> [��]
```
�C���f�b�N�X�t����map�֐�

## ���X�g�̐���

### sort
```
sort : [��] -> [��]
```
���X�g���\�[�g���܂��B
