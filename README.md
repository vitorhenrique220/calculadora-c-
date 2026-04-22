# calculadora-c-
calculadora feita em trabalho do Sérgio na bne.

using System;
using System.ComponentModel.Design;

class Program
{
    static void Main()
    {


        string casa, apartamento, nome;
        double area, valorMetro, aluguel, valortotalAluguel;





       
        Console.WriteLine("Essa é a calculadora de aluguel, para calcular o valor do aluguel do seu imovel, digite as seguintes informações:");

        Console.WriteLine("Qual o seu nome?");
        nome = Console.ReadLine();

        Console.WriteLine("Você deseja uma casa ou um apartamento?");
        casa = Console.ReadLine();

        Console.WriteLine("Digite a area do imovel:"); 
        area = double.Parse(Console.ReadLine());

        Console.WriteLine("Digite o valor do metro quadrado:");
        valorMetro = double.Parse(Console.ReadLine());

        Console.WriteLine("Digite o numero de quartos");
        int quartos = int.Parse(Console.ReadLine());


       
        double valorTotal = area * valorMetro;
        int valorQuartos = quartos;
        
        Console.WriteLine("O Valor total de metros é:" + valorTotal);
        

        if (valorQuartos > 4);
        valortotalAluguel = valorQuartos * 100;
        Console.WriteLine("o valor total do aluguel é:" + valorQuartos * valortotalAluguel);
       
    }
}
    
            // pra cima de 4 quartos considera tudo igual 4 quartos, o valor sera igual mesmo se for 5 quartos, 6 quartos, etc. 
