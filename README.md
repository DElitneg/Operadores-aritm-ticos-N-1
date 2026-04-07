# Operadores-aritm-ticos-N-1

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication2
{
    class Program
    {

        static void Main(string[] args)
        {
            Double a, b;

            Console.WriteLine("Introduzca el primer valor ");
            a = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Introduzca el segundo valor ");
            b = Convert.ToInt32(Console.ReadLine());

            Double resultSuma;
            Double resultResta;
            Double resultMultiplicacion;
            Double resultDivision;

            resultSuma = a + b;
            resultResta = a - b;
            resultMultiplicacion = a * b;
            resultDivision = a / b;

            Console.WriteLine("La suma de " + a + " más " + b + " es igual a " + resultSuma);
            Console.WriteLine("La resta de " + a + " menos " + b + " es igual a " + resultResta);
            Console.WriteLine("La multiplicación de " + a + " por " + b + " es igual a " + resultMultiplicacion);
            Console.WriteLine("La división de " + a + " dividido " + b + " es igual a " + resultDivision);
        }
    }
}
