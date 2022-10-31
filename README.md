# h-t-31.10
// задание 1
#include <iostream>
using namespace std;

int main()
{
    setlocale (LC_ALL, "RU");
    int t;
    cout << "Введите время, за которое вы бы хотели прибыть в пункт назначения (в часах)" << endl;
    cin >> t;
    int s;
    cout << "Введите расстояние до пункта назначения (в километрах)" << endl;
    cin >> s;
    cout << "Рекомендуемая скорость, чтобы добраться в пункт назначения вовремя - " << s / t << " километров в час" <<endl;
}
// проверка
Введите время, за которое вы бы хотели прибыть в пункт назначения (в часах)
2
Введите расстояние до пункта назначения (в километрах)
150
Рекомендуемая скорость, чтобы добраться в пункт назначения вовремя - 75 километров в час


...Program finished with exit code 0
Press ENTER to exit console.

// задание 2
#include <iostream>
using namespace std;

int main()
{
    setlocale (LC_ALL, "RU");
    int h1;
    int m1;
    int s1;
    cout << "Введите время в часах " << endl;
    cin >> h1;
    cout << "Введите время в минутах (X часов и ... минут) " << endl;
    cin >> m1;
    cout << " Введите время в секундах (X часов, Y минут и ... секунд)" << endl;
    cin >> s1;
    float t1;
    t1 = h1*60 + m1 + s1/60;
    float t2;
    int h2;
    int m2;
    int s2;
    cout << "Введите время окончания поездки в часах " << endl;
    cin >> h2;
    cout << "Введите время окончания поездки в минутах (X часов и ... минут) " << endl;
    cin >> m2;
    cout << " Введите время окончания поездки в секундах (X часов, Y минут и ... секунд)" << endl;
    cin >> s2,
    t2 = h2*60 + m2 + s2/60;
    float t3;
    t3 = t2 - t1;
    float p = t3*2;
    cout << " Стоимость вашей поездки составила " << p << " гривень " << endl;
}
// проверка
Введите время в часах 
2
Введите время в минутах (X часов и ... минут) 
30
 Введите время в секундах (X часов, Y минут и ... секунд)
0
Введите время окончания поездки в часах 
3
Введите время окончания поездки в минутах (X часов и ... минут) 
0
 Введите время окончания поездки в секундах (X часов, Y минут и ... секунд)
0
 Стоимость вашей поездки составила 60 гривень 


...Program finished with exit code 0
Press ENTER to exit console.

// задание 3
#include <iostream>
using namespace std;

int main()
{
    setlocale (LC_ALL, "RU");
    float s1;
    float s2;
    float s3;
    float v1;
    float v2;
    float v3;
    float p1;
    float p2;
    float p3;
    cout << "Введите расстояние, которое необходимо проехать на первом виде бензина" << endl;
    cin >> s1;
    cout << "Введите расход первого вида бензина на 100 км  (в литрах)" << endl;
    cin >> v1;
    cout << "Введите цену первого вида бензина за литр" << endl;
    cin >> p1;
    cout << "Введите расстояние, которое необходимо проехать на втором виде бензина" << endl;
    cin >> s2;
    cout << "Введите расход второго вида бензина на 100 км (в литрах)" << endl;
    cin >> v2;
    cout << "Введите цену второго вида бензина за литр" << endl;
    cin >> p2;
    cout << "Введите расстояние, которое необходимо проехать на третьем виде бензина" << endl;
    cin >> s3;
    cout << "Введите расход третьего вида бензина на 100 км (в литрах)" << endl;
    cin >> v3;
    cout << "Введите цену третьего вида бензина за литр" << endl;
    cin >> p3;
    float c1;
    c1 = (s1 / 100)*v1*p1;
    float c2;
    c2 = (s2 / 100)*v2*p2;
    float c3;
    c3 = (s3 / 100)*v3*p3;
    cout << "Стоимость вашей поездки, если ваш выбор пал на 1 вид бензина " << c1 << endl;
    cout << "Стоимость вашей поездки, если ваш выбор пал на 2 вид бензина " << c2 << endl;
    cout << "Стоимость вашей поездки, если ваш выбор пал на 3 вид бензина " << c3 << endl;
}
// проверка
Введите расстояние, которое необходимо проехать на первом виде бензина
100
Введите расход первого вида бензина на 100 км  (в литрах)
7
Введите цену первого вида бензина за литр
2
Введите расстояние, которое необходимо проехать на втором виде бензина
100
Введите расход второго вида бензина на 100 км (в литрах)
1
Введите цену второго вида бензина за литр
3
Введите расстояние, которое необходимо проехать на третьем виде бензина
100
Введите расход третьего вида бензина на 100 км (в литрах)
30
Введите цену третьего вида бензина за литр
1.5
Стоимость вашей поездки, если ваш выбор пал на 1 вид бензина 14
Стоимость вашей поездки, если ваш выбор пал на 2 вид бензина 3
Стоимость вашей поездки, если ваш выбор пал на 3 вид бензина 45


...Program finished with exit code 0
Press ENTER to exit console.
