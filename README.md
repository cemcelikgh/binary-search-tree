# binary-search-tree
Patika Beginner Frontend Web Development Path Certification Task
<br>Binary Search Tree

<br>

[ 7, 5, 1, 8, 3, 6, 0, 9, 4, 2 ]

root: 7

```
7
```

insert: 5, 7'nin soluna yerleştirilir

```
  7
 /
5
```

insert: 1; 7'nin soluna, 5'in soluna yerleştirilir

```
    7
   /
  5
 /
1
```

insert: 8; 7'nin sağına yerleştirilir

```
    7
   / \
  5   8
 /
1
```

insert: 3; 7'nin soluna, 5'in soluna, 1'in sağına yerleştirilir

```
    7
   / \
  5   8
 /
1
 \
  3
```

insert: 6; 7'nin soluna, 5'in sağına yerleştirilir

```
    7
   / \
  5   8
 / \
1   6
 \
  3
```

insert: 0; 7'nin soluna, 5'in soluna, 1'in soluna yerleştirilir

```
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
```

insert: 9; 7'nin sağına, 8'in sağına yerleştirilir

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
```

insert: 4; 7'nin soluna, 5'in soluna, 1'in sağına; 3'ün sağına yerleştirilir

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
```
insert: 2; 7'nin soluna, 5'in soluna, 1'in sağına, 3'ün soluna yerleştirilir

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```
