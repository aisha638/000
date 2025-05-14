#import random

print("Привет! Я загадал число от 1 до 10. Угадай его!")

secret_number = random.randint(1, 10)

guess = int(input("Твоя догадка: "))

if guess == secret_number:
    print("Правильно! Молодец!")
else:
    print("Неправильно. Я загадал число", secret_number)