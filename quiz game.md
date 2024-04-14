#a quiz game in python language  idle 3.10.0

print("welocome to my computer quiz!")
playing =input("do you want to play? ")
print(playing)
if playing.lower() != "yes":
    quit()
print("okay! let's play: )")
score = 0

answer = input("what does CPU stand for?")
if answer.lower() == "central processing unit":
    print("correct!")
    score +=1
else:
    print("incorrect!")
    
answer = input("WHO stands for?")
if answer.lower() == "world health organization":
    print("correct!")
    score +=1
else:
    print("incorrect!")
    
answer = input("what does GPU stand for?")
if answer.lower() == "graphics processing unit":
    print("correct!")
    score +=1
else:
    print("incorrect!")

answer = input("what is RAM stand for?")
if answer.lower() == "random access memory":
    print("correct!")
    score +=1
else:
    print("incorrect!")

answer = input("what is RAM stand for?")
if answer.lower() == "random access memory":
    print("correct!")
    score +=1
else:
    print("incorrect!")

print("you got " +str(score) + " questions correct!")
print("you got " +str((score/5)*100) + " % questions correct!")







