# CIS567-integrated-lab-2
Integrated Lab
# Get the input from the user
input_string = input()

# Split the input into the character and the phrase
char = input_string[0]
phrase = input_string[2:]

# Count the occurrences of the character in the phrase
count = phrase.count(char)

# Determine if the output should be singular or plural
if count == 1:
    print(f"{count} {char}")
else:
    print(f"{count} {char}'s")
