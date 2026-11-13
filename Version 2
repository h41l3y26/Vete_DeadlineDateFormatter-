import datetime

#Do array for months
months= ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]

#Get the information
event_title= input("Enter event title: ")
year= int(input("Enter year: "))
month= int(input("Enter month: "))
day= int(input("Enter day: "))


real_month= months[ month - 1]
date_obj=datetime.date(year, month, day)
weekday_name=date_obj.strftime("%A")

#Print the output
print("")
print("Formatted Output:")
print("Event: ", event_title.upper())
print("Date: ", real_month, day, year)
print("Year: ", year)

print("Day: ", day)
print("Weekday: ", weekday_name)
print("Month; ", real_month)
