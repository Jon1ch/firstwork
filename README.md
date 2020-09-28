def arithmetic (a, b, c):

    if c == "+":

        return a + b

    elif c == "-":

        return a - b

    elif c == "*":

        return a * b

    elif c == "/":

        return a / b

    else:

        return "Неизвестная операция!"

result = arithmetic (int(input("Введите число a")), int(input("Введите число b")), input("Введите операцию:"))

print("Результат: ", result)
