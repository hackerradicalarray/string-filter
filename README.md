# string-filter
START
  Initialize empty array output_strings
  
  Read number of strings n
  
  For i = 1 to n
    Read string from input
    If length of string <= 3
      Add string to output_strings
  
  Print output_strings
END
# Filter Short Strings Program

This Python program filters an array of strings to create a new array containing only strings with a length less than or equal to 3 characters.

### How to Use

1. Clone the repository:
   ```bash
   git clone <repository-url>
python filter_short_strings.py

### 4. Написать программу

Создадим файл `filter_short_strings.py`, который будет содержать код программы для фильтрации массива строк.

def filter_strings(input_strings):
    output_strings = []
    for string in input_strings:
        if len(string) <= 3:
            output_strings.append(string)
    return output_strings

def main():
    n = int(input("Enter the number of strings: "))
    strings = []
    for i in range(n):
        string = input(f"Enter string {i + 1}: ")
        strings.append(string)

    filtered_strings = filter_strings(strings)
    print("Filtered strings:", filtered_strings)

if __name__ == "__main__":
    main()

