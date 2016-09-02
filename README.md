# How-old-am-I

print("How old are you in seconds, minutes, hours, days, months, and years?")

name = input("name: ")

print("Enter today's date, in the order of year, month, day"

CurrentYear = int(input("current year: "))

CurrentMonth = int(input("current month: "))

CurrentDay = int(input("current day: "))

print("Enter your birthday in the same order")

BirthYear = int(input("year: "))

BirthMonth = int(input("month: "))

BirthDay = int(input("day: "))

def AgeCalculator(name, CurrentYear, CurrentMonth, CurrentDay, BirthYear, BirthMonth, BirthDay)

if BirthMonth <= CurrentMonth:
    AgeInYears = CurrentYear - BirthYear
    AgeInMonths = AgeInYears*12 + CurrentMonth - BirthMonth
    
      if CurrentDay >= BirthDay
      AgeInDays = AgeInMonths*30 + AgeinYears*5 + CurrentDay - BirthDay
      AgeInHours = AgeInDays*24
      AgeInMinutes = AgeInHours*60
      AgeinSeconds = AgeInMinutes*60
      
      Else CurrentDay < BirthDay
      AgeInDays = AgeInMonths*30 + AgeinYears*5 + BirthDay - CurrentDay
      AgeInHours = AgeInDays*24
      AgeInMinutes = AgeInHours*60
      AgeinSeconds = AgeInMinutes*60
      
else BirthMonth >= CurrentMonth
    AgeInYears = CurrentYear - BirthYear
    AgeInMonths = AgeInYears*12 - CurrentMonth + BirthMonth
    
      if CurrentDay >= BirthDay
      AgeInDays = AgeInMonths*30 + AgeinYears*5 + CurrentDay - BirthDay
      AgeInHours = AgeInDays*24
      AgeInMinutes = AgeInHours*60
      AgeinSeconds = AgeInMinutes*60
      
      Else CurrentDay < BirthDay
      AgeInDays = AgeInMonths*30 + AgeinYears*5 + BirthDay - CurrentDay
      AgeInHours = AgeInDays*24
      AgeInMinutes = AgeInHours*60
      AgeinSeconds = AgeInMinutes*60
      
print (name, "has been alive for", AgeInSeconds, "seconds", AgeInMinutes, "minutes", AgeInHours, "hours", AgeInDays, "days", AgeInMonths, "months", AgeInYears, "years.")
