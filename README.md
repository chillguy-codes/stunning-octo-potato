# stunning-octo-potato
# my first mini game: Guess the number!
print("Пробуй угадать число от 0 до 10!")
a = int(input())
while a > 0:
    a = int(input("Введите число: "))
    print("Попробуй другое число!")
if a == 0:
    print("Ты угадал!")
