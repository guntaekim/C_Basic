# 2023-03-23 4주차 c언어 실습

```C

#define _CRT_SECURE_NO_WARRINGS
#include <stdio.h>

int main(void)
{

    int money, exchange;            //
    int price, c1000, c500, c100;  //
    printf("물건 값을 입력하시오:");
    scanf ("%d",&price);
    printf("투입한 금액을 입력하시오::");
    scanf ("%d",&money);
    printf("거스름돈은 다음과 같습니다.");
    
    exchange = money - price; //

    c1000 = exchange/1000;  //
    exchange = exchange%1000;      //

    c500 = exchange/500;    //
    exchange = exchange%500;    //

    c100 = exchange/100;    //
    exchange = exchange/100;    //

    printf("\n천원권:%d장\n", c1000);     //
    printf("오백원 동전 %d개\n,", c500);  //
    printf("백원 동전:%d개\n",c100);    //
    return 0;
        



} 
```
