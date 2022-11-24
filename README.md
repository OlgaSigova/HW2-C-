# HW2-C-
домашнее задание к семинару 2


Task_1
// Напишите программу, которая принимает на вход трёхзначное число
// и на выходе показывает вторую цифру этого числа.

// 456 -> 5
// 782 -> 8
// 918 -> 1
int num = new Random().Next(100, 1000);
Console.WriteLine(num);
int result = (num % 100) / 10;
Console.WriteLine(result);



Task_2
//Напишите программу, которая выводит третью цифру 
//заданного числа или сообщает, что третьей цифры нет.

//645 -> 5
//78 -> третьей цифры нет
//32679 -> 6

int num = new Random().Next(10,1000);
Console.WriteLine(num);
if (num>100)
{
Console.WriteLine((num%100)%10);
}
else {
  Console.WriteLine("Третьего числа нет");  
}



Task_3
//  Напишите программу, которая принимает на вход цифру,
//обозначающую день недели, и проверяет, 
//является ли этот день выходным.

//6 -> да
//7 -> да
//1 -> нет


int num = new Random().Next(1, 7);
Console.WriteLine(num);
if ((num == 6) || (num == 7))
{
    Console.WriteLine("ДА");
}
else

    Console.WriteLine("НЕТ");
