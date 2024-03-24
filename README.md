# Correct-Age
This program is to calculate the correct age of the person by user input information
Import statements:
import datetime: Imports the datetime module, which contains classes for handling dates and times.
import pyttsx3: This imports the pyttsx3 module, a Python text-to-speech conversion package.

Function talk (text):
This method accepts a string of text as input and turns it to voice using the pyttsx3 library.
It starts a pyttsx3 engine, sets settings like rate (speed of speech) and loudness, selects a voice, reads the text, and then runs the engine to convert it to speech.
Classification: human
This class portrays the human being.
Constructor (the __init__ method)
It initializes numerous characteristics of a person object, including name, age, and date_of_birth.
It invites the user to enter the name, age, year of birth, month of birth, and day of birth of a person.
It uses the datetime.date class to compute the user's birth date.
It prints and reads the entered information about the person.

Method: find(self)
This approach estimates the person's true age in years.
The age is calculated by subtracting the current date from the date of birth.
It prints and calls out the person's exact age.

Creating an instance of the Human Class:

The human class generates an instance named person.
The user is invited to provide information about the individual, such as their name, age, and date of birth.

The discover method of the person object is then invoked to obtain and publish the individual's exact age.
This code allow users to enter information about a person (name, age, and date of birth) and then calculates and displays the individual's exact age. It also uses text-to-speech capability to convey information vocally.

the below is the code:-
# import datetime
# import pyttsx3
# def speak(text):
#     engine=pyttsx3.init()
#     engine.setProperty('rate', 130)  
#     engine.setProperty('volume', 190)  
#     engine.setProperty("voice","english_rp")
#     engine.say(text)
#     engine.runAndWait()

# class human:
#     def __init__(self):
#         self.name=input("enter the name of the person:- ")
#         self.age=int(input("enter the age of a person:- "))
#         self.country=input("enter your country name where you were bron:- ")
#         self.year_birth = int(input("Enter the year of birth (YYYY): "))
#         self.month_birth = int(input("Enter the month of birth (MM): "))
#         self.day_birth = int(input("Enter the day of birth (DD): "))
#         self.date_birth=datetime.date(self.year_birth,self.month_birth,self.day_birth)
#         print(f"your name is {self.name}, your age is {self.age} and your date of birth is {self.date_birth}, place of birth {self.country}")
#         speak(f"your name is {self.name}, your age is {self.age} and your date of birth is {self.date_birth}, place of birth is {self.country}")
#     def find(self):
#         today=datetime.date.today()
#         age=today-self.date_birth
#         age_days=age.days
#         age_years=age_days//365
#         print(f"your correct age is--{age_years}--please dont messup with your age")
#         speak(f"your correct age is--{age_years}--please dont messup with your age")

    
# person=human()
# person.find()


