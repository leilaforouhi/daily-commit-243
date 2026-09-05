def find_longest_word(words):
    if not words:
        return ""

    return max(words, key=len)


if __name__ == "__main__":
    words = ["python", "repository", "commit", "development"]
    print("Words:", words)
    print("Longest word:", find_longest_word(words))
