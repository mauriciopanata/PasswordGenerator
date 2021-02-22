# @mauriciopanata - San Diego, CA - 02/21/2021

import random
import string


class PasswordGenerator:
    def __init__(self):
        while True:
            x_factor = int(input("Enter length of your Password "))
            print("".join(random.choices(string.printable, k=int(x_factor))))
            while True:
                answer = str(input('Run again? (y/n): '))
                if answer in ('y', 'n'):
                    break
                print("invalid input.")
            if answer == 'y':
                continue
            else:
                print("Goodbye")
                break


PasswordGenerator()
