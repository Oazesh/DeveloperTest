using System;
using System.Linq;

namespace Library
{
    public class ZadanieOne
    {
        public static void One() // Вывод чисел в консоль от 1 до N через запятую
        {
            Console.Write("Введите число N: ");
            int n = int.Parse(Console.ReadLine());
            if (n <= 0)
            {
                Console.WriteLine("Число должно быть положительным и больше нуля.");
                return;
            }
            string result = string.Join(", ", Enumerable.Range(1, n));
            Console.WriteLine(result);
        }
    }

    public class ZadanieTwo
    {
        public static void Two() // Отрисовываем квадрат из символов "#", оставляю внутри пробел
        {
            Console.Write("Введите нечетное число N: ");
            int n = int.Parse(Console.ReadLine());
            if (n % 2 == 0) // Если N - четное число, завершаем функцию
            {
                Console.WriteLine("Вы ввели четное N.");
                return;
            }
            for (int row = 1; row <= n; row++)
            {
                for (int col = 1; col <= n; col++)
                {
                    if (row == n / 2 + 1 && col == n / 2 + 1) // Проверка на центр квадрата, если - true, то ставим пробел
                        Console.Write(" ");
                    else // В остальных случаях ставим символ #
                        Console.Write("#");
                }
                Console.WriteLine();
            }
        }
    }

    public class Program
    {
        static void Main(string[] args) // Пример вызова методов классов ZadanieOne и ZadanieTwo.
        {
            ZadanieOne.One();
            ZadanieTwo.Two();
        }
    }
}

/*
Как модифицировал: 
В методе "One" необходимо добавить проверку на ввод отрицательного числа или нуля. В данном случае метод вернет пустую строку, что не будет соответствовать требованию.

В методе "Two" лучше использовать символ " " (пробел) вместо строки " " (пробел в кавычках), чтобы избежать создания нового объекта строки при каждом выводе пробела.

Добавление комментариев к коду может улучшить его читаемость и понимание другими программистами.
 */
