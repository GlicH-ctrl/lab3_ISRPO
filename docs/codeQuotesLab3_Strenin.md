# Блоки кода и цитаты в Markdown

## Inline-код
Команда `git status` показывает состояние репозитория.

Команда `git add .` добавляет все файлы в staging area.

## Блоки кода с подсветкой синтаксиса

### Пример на Python:
```python
def hello_world():
    name = input("Введите ваше имя: ")
    print(f"Привет, {name}!")
    return True

hello_world()
```

```csharp
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Введите число:");
        int number = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine($"Вы ввели: {number}");
    }
}
```

Это просто блок текста
без подсветки синтаксиса
Можно писать любые строки