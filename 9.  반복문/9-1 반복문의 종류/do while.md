#### 일단 반복할 문장을 한번 수행하고 반복문의 끝부분에서 조건식을 검사해서 루프를 탈출할지 결정한다.(반드시 한번은 반복할 문장을 수행한다.) ####
___

## do while의 기본 ##

```c
i = 0;
do
	printf("%d ", i++); // 반복할 문장
while (i < 10); // 조건식
```

## do while의 사용 예 ##
```c
# include <stdio.h>
int main(void)
{
	int i = 0;
	do
		printf("%d ", i++);
	while (i < 10);
	printf("\n");

	return 0;
	// 0 1 2 3 4 5 6 7 8 9
}
```