score = int(input("Enter the student's score: "))

if score >= 70 and score <= 100:
Grade=A
elif score >= 60 and score <= 69:
    Grade=B
elif score >= 50 and score <= 59:
    Grade=C
elif score >= 45 and score <= 49:
  Grade=D
elif score >= 40 and score <= 44:
  Grade=E
elif score >= 0 and score <= 39:
  Grade=F
else:
    print("Invalid score")


Print(score"="Grade)
