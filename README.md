#include <stdio.h>

int main(){
float BanKinh;
const float PI = 3.14;
float ChuVi;
float Dientich;
printf("\n\n CHUONG TRINH BAN KINH , DIEN TICH CHU VI HINH TRON\n");
printf(" Nhap ban kinh di ban yeu oi: ");
scanf("%f", &BanKinh);
ChuVi = 2*BanKinh*PI;
Dientich = BanKinh*BanKinh*PI;
printf(" Chu vi hinh tron la: %.2f\n", ChuVi);
printf(" Dien tich hinh tron la: %.2f\n\n", Dientich);
return 0;
}
