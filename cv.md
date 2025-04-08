# Cherkas Timofey ASOIR-231

## Contacts
* Phone number: +375(29)353-54-42  
* E-mail: cc.timofey@mail.ru  
* Telegram: [@Uwannatell](https://t.me/Uwannatell)  
* GitHub: [ll.timofey](https://github.com/lltimofey)  
* Instagram: [ll.timofey](https://www.instagram.com/ll.timofey/)  

## О себе
Student majoring in computer science and computer engineering. Looking for an opportunity to improve my skills.
I value the opportunity to learn new things and am open to internships and startup projects where I can apply my knowledge and develop my skills.

## Skills
- Git (basic)
- HTML, CSS
- C#

## English level
I have an A1 (Beginner) level of English, which allows me to work with obtaining technical documentation.

## Примеры кода
### Is Number Positive and Even?
```csharp
Console.Write("Введите число: ");
int number = int.Parse(Console.ReadLine()!);

if (number > 0 && number % 2 == 0)
{
    Console.WriteLine("Число положительное и чётное");
}
else
{
    Console.WriteLine("Условия не выполнены");
}
```
### Finding Perfect Numbers
```csharp
internal class Program
{
    static void Main(string[] args)
    {
        Console.Write("Enter k: ");
        int k = int.Parse(Console.ReadLine()!);

        for (int i = 1; i <= k; i++)
        {
            if (IsPerfectNumber(i))
            {
                Console.WriteLine($"{i} - perfect number");
            }
            else
            {
                Console.WriteLine($"{i} - not a perfect number");
            }
        }
    }

    public static bool IsPerfectNumber(int number)
    {
        if (number < 2) return false; // Совершенные числа начинаются с 6

        int sum = 0;
        for (int i = 1; i <= number / 2; i++)
        {
            if (number % i == 0)
            {
                sum += i;
            }
        }

        return sum == number;
    }
}
```

## Примеры работ

![CaughtIn8kCaightIn8kMemeeGIF (2)](https://github.com/user-attachments/assets/9b505931-6c70-4f80-b59b-296456c58ba4)
![CaughtIn8kCaightIn8kMemeeGIF](https://github.com/user-attachments/assets/1a01ab43-5425-4a53-a4ba-3c299704104a)
