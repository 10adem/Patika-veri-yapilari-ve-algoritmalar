# Proje 1

## Soru 1

[22,27,16,2,18,6]

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?

```
[22,27,16,2,18,6] n

[2,27,16,22,18,6] n-1

[2,6,16,22,18,27] n-2

[2,6,16,18,22,27] 1
```

Big-O :

```
n+(n-1)+(n-2)+1

n.(n+1)/2

(n*n)+n/2

O(n*n)
```

Time Complexity :

```
Average Case olur.
```

## Soru 2

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

```
[7,3,5,8,2,9,4,15,6] n

[2,3,5,8,7,9,4,15,6] n-1

[2,3,4,8,7,9,5,15,6] n-2

[2,3,4,5,7,9,8,15,6] n-3

[2,3,4,5,6,9,8,15,7] n-4

[2,3,4,5,6,7,8,15,9] n-5

[2,3,4,5,6,7,8,9,15] 1

```
