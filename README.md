def count_words():
# Prompt the user to enter a sentence or paragraph
user_input = input("Please enter a sentence or paragraph: ")
    
# Check if the input is empty
if not user_input.strip():
        print("Error: No input provided. Please enter a valid sentence or paragraph.")
        return
    
 # Split the input into words and count them
   words = user_input.split()
    word_count = len(words)
    
# Display the word count to the console
   print(f"The number of words in your input is: {word_count}")

# Run the word count function
count_words()
