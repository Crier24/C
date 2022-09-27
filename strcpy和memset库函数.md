# C
//strcpy--string copy字符串拷贝
#include <stdio.h>
#include <string.h>
int main() {
	char arr1[] = "bit";
	char arr2[20] = "########";
	strcpy(arr2, arr1);
	printf("%s\n", arr2);
	return 0;
}

#include <string.h>
#include <stdio.h>
//memset--memory set内存设置
int main() {
	char arr[] = "hello world";
	memset(arr, '*', 5);
	printf("%s\n", arr);
	return 0;
}
