<pre>
#include <iostream>

using namespace std;

//y= 6x^5 − 8x^4 + 2x^3 − 3x + 5 fonksiyonunun 4. dereceden türevi nedir?
//1. Dereceden; F’(x) = 30x^4 - 32x^3 + 6x^2 - 3
//2. dereceden; F’’(x) = 120x^3 - 96x^2 + 12x
//3. Dereceden; F’’’(x) = 360x^2 - 192x + 12
//4. dereceden; F’’’’(x) = 720x - 192

double fourth_derivative_q9(double x)
{
    return 720.0 * x - 192.0;
}

int main()
{
    double x_q9;

    cout << "Bir x değeri giriniz: ";
    if (!(cin >> x_q9))
    {
        cout << "Hata! Lütfen bir sayı giriniz." << endl;
        return 1;
    }

    double result_q9 = fourth_derivative_q9(x_q9);

    cout << "4. Dereceden Türev Formülü: 720x - 192" << endl;
    cout << "Girilen x = " << x_q9 << " için 4. dereceden türevinin değeri: " << result_q9 << endl;

    return 0;
}
</pre>
