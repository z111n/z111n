import math

def Main():
    result = Calculate()
    Print_Number(result)


def Calculate():
    result = (3 * 5 * 10 * math.sqrt(49)) / (math.fabs(-10) * (0.01**(1/3)))
    return result


def Print_Number(result):
    print(result)


if __name__ == "__main__":
    Main()
