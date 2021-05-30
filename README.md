# code-in-place-final-project
Code In Place 2021 Final Project
"""
Prompts the user for their name and then says hello to start gratitude journal.
"""

def main():
    question_1 = input("What is your name? ")
    print("Hello " + str(question) + "!")

    question_2 = input("How are you feeling right now? ")
    print("What do you want to do when you're feeling " + str(question_2) + "?")

    # If the user answers with Yes, respond with good job
    # If the user answers with No, respond with drink some water
    question_3 = input("Did you drink water today? ")
    if int(user_answer) == Yes:
        print("Good job!")
    else:
        print("Take a break and get some water!")

if __name__ == '__main__':
    main()
