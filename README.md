# File-Handling
Program to read data from a file and print it
file_path = "example.txt"

try:
    with open(file_path, "r") as file:
        content = file.read()
        print(content)
except FileNotFoundError:
    print(f"File {file_path} not found.")
