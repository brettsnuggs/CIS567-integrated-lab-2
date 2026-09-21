# CIS567-integrated-lab-2

user_input = input()

character = user_input[0]
phrase = user_input[2:]

count = phrase.count(character)

if count == 1:
    print(f"1 {character}")
else:
    print(f"{count} {character}'s")
