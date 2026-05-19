# -Developer-beginner-
with open("sathya.txt", "w") as file:
    file.write("sathya-eee\n")

with open("sathya.txt", "a") as file:
    file.write("3rd year eee\n")

with open("sathya.txt", "r") as file:
    content = file.read()
    print(content)
    
