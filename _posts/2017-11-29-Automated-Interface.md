---
title: Automated Interface
layout: post
author: noah.parry
permalink: /automated-interface/
source-id: 13DbD65K1tyJo2EFzqVJq5DYCpGg-JczeI-B3c0nadfg
published: true
---
Automated Interface

*By Noah Parry*

print("hello, what is your name?")

resp1=input()

print("hello " + resp1 + "!")

#ans=0

while True:

  resp2=input("how are you today? (good or bad???)")

  if resp2.lower()== "good":

    print("i'm so glad " + resp1 + "!")

    #ans=0

    break

  elif resp2.lower()== "bad":

    print("oh i'm so sad to hear that... i'm great!")

    #ans=0

    break

  else:

    print("go away you despicable human being!!!")

    #ans=1

print( "here are 3 questions...")

resp3=input("are you :\n A) a fish \n B) a banana \n C) a ninja \n D) a snake")

if resp3.lower()== "A" or "D":

  print("ooh " + resp1 + ",interesting!")

elif resp3.lower()== "B":

  print("Yummy!!!")

elif resp3.lower()== "C":

  print(" i dont believe you... but OK!")

else:

  print("thats not an option " + resp1 + "!")

print("next question...")

resp4=input("do you like: \n A) CHEESE \n B) SAUSAGES \n C) BREAD")

if resp4.lower()=="A" or "B":

  print("Me too!")

elif resp4.lower()== "C":

  print("OK, I dont like that, but good for you!")

print("one last question...")

resp5=input("are you a \n A) dog person\n B) a cat person")

if resp5.lower()== "A":

  print("no way! me too!")

elif resp5.lower()== "B":

  print("I have had enough of you, you cat loving, cheese eating easily annoyed person! ")

This immense block of code is basically, a very large collection of questions. Now, the problem for most people is that they think there has to be artificial  intelligence to achieve AI like this, but effectively, all you need to do is manipulate their options. As seen above, without me having given the person responding options to choose from, there could have been any number of different words used, whereas me giving them options makes sure I can deal with anything that they throw at me.

If I have learned one thing from this lesson, it is that if there isn't a way to prepare for everything, you should always limit what they can use against you. You can’t prepare for everything, but they can’t  say everything, not when you have restricted their options as well as I have.

Hoping to have made my code even better next week, 

Noah

PS. here is a link to my actual code [https://repl.it/@noahparry/NaughtyAdeptAlbacoretuna](https://repl.it/@noahparry/NaughtyAdeptAlbacoretuna)

