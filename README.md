<h1>Домашнее задание по теме 5. Использование функций стандартной библиотеки языка Си</>

<h2>Задача - выполнить вычислений</h2>

<h2>Условия задачи</h2>
<p>Решить пример при помощи функций языка Си.</p>
<img width="633" height="92" alt="example" src="https://github.com/user-attachments/assets/45940979-983e-46ad-9736-4af805f2648a"/>

<h2>Блок-схема</h2>
<img width="180" height="430" alt="diagram_hw5" src="https://github.com/user-attachments/assets/7e1c1458-42c7-4bde-ad98-238476b6d8f9"/>

<h2>Код</h2>

```c
#include <stdio.h>
#include <math.h>

void main() {
	// параметры
	double x = -15.246;
	double y = 4.642e-2;
	double z = 20.001e2;

	double alpha;

	// решение
	alpha = log(pow(y, -sqrt(-x))) * (x - (y / 2.0)) + pow(sin(atan(z)), 2);

	// вывод результат
	printf("Результат - %.3f\n", alpha);
}
```
