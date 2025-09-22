def count_lines(filename):
    try:
        with open(filename, "r") as f:
            return sum(1 for _ in )
    except FileNotFoundError:
        return 0

if __name__ == "__main__":
    file_name = "note.txt"
    print(f"Number of lines in '{file_name}': {count_lines(file_name)}")
