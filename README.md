# love-calculator
# making a love calculator
# 1st creating input for name
print("The love Calculator printing your love score..........")
name1 = input( )
name2 = input( )
# combining the both name in together
combine_name = name1 + name2
lower_names = combine_name.lower()
# creating a system1
t = lower_names.count("t")
r = lower_names.count("r")
u = lower_names.count("u")
e = lower_names.count("e")
first_digit = t + r + u + e
# system2
l = lower_names.count("l")
o = lower_names.count("o")
v = lower_names.count("v")
e = lower_names.count("e")
second_digit = l + o + v + e
# now we have total 
score = int(str(first_digit) + str(second_digit))
# and giving the condition
if (score < 10) or (score > 90):
    print(f"Your score is {score}, you go together coke and mentos.")
elif (score >= 40) and (score <= 50):
    print(f"Your score is {score}, you are alright together.")
else:
    print(f"Your score is {score}.")
