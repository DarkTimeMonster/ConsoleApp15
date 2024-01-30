Отчет по компьютерному практикуму № 15

    using System;
    using System.Collections.Generic;
    using System.Linq;
    using System.Text;
    using System.Threading.Tasks;

    namespace ConsoleApp15
    {
    internal class Program
    {
        static void Main(string[] args)
        {

            /*
            for(int x = -5; x<=5 ;x+=2)
            {
            Console.WriteLine($"y = {-5 * Math.Pow(x,2)+2*x+1}, при x = {x}");
            }*/
            //Условие задачи:Вывксти двузначные числа кратные 11
            /*
            int i = 0;
            int y = 0;
            for (int x = 10; x <= 100; x++)
            {
                if (x % 11 == 0)
                {
                    i++;
                    Console.WriteLine($"Числа {x}");
                    y = x + y;
                }
            }
            Console.WriteLine($"Кол-во {i}");
            Console.WriteLine($"Cумма {y}");
            */
            double fx;
            for (double x = 1; x <= 8; x+=0.2)
            {
               fx = 0.5 * Math.Pow( x - 5 ,2);
                Console.WriteLine($"f(x) = {fx:f2}, при x = {x}");
            }

            Console.ReadKey();
        }
    }
}
