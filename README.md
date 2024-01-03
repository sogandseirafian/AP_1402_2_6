# AP_1402_2_6
using System;
using System.Collections.Generic;
using System.Linq;
using System.Runtime.CompilerServices;
using System.Security.Cryptography.X509Certificates;
using System.Text;
using System.Threading.Tasks;

namespace AP_1402_2_4CS
{
    internal class Program
    {
        static void Main(string[] args)
        {
            double min = Convert.ToDouble(Console.ReadLine());
            double fainal = Convert.ToDouble(Console.ReadLine());
            math1(min, fainal);

        }
        static void math1(double x, double y)
            {
               double Result = 0.35  * x +0.65 * y;
               Console.WriteLine(Result);
             }
    }
}
