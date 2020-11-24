# Calender
# Program to display calendar of the given month and year

# importing calendar module
import calendar

yy = int(input("Enter Year: "))  # year
mm = int(input("Enter Month: "))    # month
print(calendar.month(yy, mm))
