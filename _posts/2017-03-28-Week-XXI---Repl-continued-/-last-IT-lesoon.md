---
title: Week XXI - Repl continued / last IT lesoon
layout: post
author: noah.parry
permalink: /week-xxi---repl-continued-/-last-it-lesoon/
source-id: 1H8x8yiUPxbYEMNSJnJFWVLJm6KTebUTEVShHeeTXAZs
published: true
---
<table>
  <tr>
    <td>Title</td>
    <td>Week XXI - Repl continued / last IT lesoon</td>
    <td>Date</td>
    <td>28/03/17</td>
  </tr>
</table>


<table>
  <tr>
    <td>Starting point:</td>
    <td>Challenges set by my teacher</td>
  </tr>
  <tr>
    <td>Target for this lesson?</td>
    <td>To have finished the challenges set by my teacher</td>
  </tr>
  <tr>
    <td>Did I reach my target? 
(add details to "Lesson Review")</td>
    <td> No, not at this point.</td>
  </tr>
</table>


<table>
  <tr>
    <td>Lesson Review</td>
  </tr>
  <tr>
    <td>How did I learn? What strategies were effective? </td>
  </tr>
  <tr>
    <td>def main():
  greeting()
  while True:
    response = select_function()
    print(response)
    
def greeting():
  print("Hello, I am a maths homework cheat. How can I help you with your math homework?")
  
def select_function():
  print("these are my funtions:")
  print("1 = rectangle perimeter")
  print("2 = rectangle area")
  print("3 = cubic volume")
  print("4 = triangle area")
  print("5 = parrolelogram area")
  print("6 = triangle perimeter")
  print(" \n I have no other options, do not select another number.")
  result = input(" \n Please select a number.")
  while True:
    if result == "1":
      l = input("what is the height?")
      w = input("what is the width?") 
      return (rectangle_perimeter(l,w))
    
    elif result == "2":
      l = input("what is the height?")
      w = input("what is the width?") 
      return (rectangle_area(l,w))
    
    elif result == "3":
      l = input("what is height?")
      d = input("what is depth?")
      w = input("what is width?")
      return (cubic_volume(l,w,d))
    
    elif result == "4":
      a = input("what is height?")
      b = input("what is the width?")
      return (triangle_area(a,b))
    
    elif result == "5":
      h = input("what is the height?")
      w = input("what is the width?")
      return (parrolelogram_area(h,w))
    
    elif result == "6":
      a = input("what is length?")
      b = input("what is other length?")
      c = input("what is final length?")
      return (triangle_perimeter(a,b,c))
    
    

def rectangle_perimeter(l,w):
  return (2 * (l + w))
  
def rectangle_area(l,w):
  return (str(l*w) + " units squared")
  
def cubic_volume(l,w,d):
  return (str(l*w*d) + " units cubed")
  
def triangle_area(a,b):
  return (str((a*b) *1/2) + " units cubed")
  
def parrolelogram_area(h,w):
  return (h*w) 
  
def triangle_perimeter(a,b,c):
  return (a + b + c) 
  


main()



This is the challenge. The code is incorrect, and it is very annoying because of this.</td>
  </tr>
  <tr>
    <td>What limited my learning? Which habits do I need to work on? </td>
  </tr>
  <tr>
    <td>The habits I need to work on are my ability to refer to previous texts ( such as 'going on a holiday' from codecademy ) to remember the things I need to know to complete the challenges. Aside from this, the lesson just passed was my last IT lesson of this academic year :-(, which means I will not need to complete blog posts anymore. </td>
  </tr>
  <tr>
    <td>What will I change for next time? How will I improve my learning?</td>
  </tr>
  <tr>
    <td>During the completion of the task I will refer back to notes from previous other activities, and troubleshoot using the ‘Traceback (most recent call last):’. This will help because gradually I will learn my mistakes and sort them out. This will improve my learning by letting know what I have done wrong, and letting me get it done and sort it out.

For the last time, 
                              Noah</td>
  </tr>
</table>


