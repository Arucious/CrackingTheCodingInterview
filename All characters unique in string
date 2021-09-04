# Implement an algorithm to determine if a string has all unique characters with no additional data structures 

# O(NlogN) to sort and then O(N) to go through it again. O(NlogN) for the algorithm. 
def isUnique(inputString):
    inputStringSorted = sorted(inputString)
    currentCharacter = ""
    currentCount = 0
    for c in inputStringSorted: 
        if c == " ": 
            continue 
        if c != currentCharacter: 
            currentCharacter = c
            currentCount = 1
            continue 
        if c == currentCharacter: 
            currentCount += 1 
        if currentCount > 1: 
            return False
    return True
    


def main():
    inputString = "abcdefg"
    result = isUnique(inputString)
    print(f"The result is {result}")


if __name__ == "__main__":
    main()