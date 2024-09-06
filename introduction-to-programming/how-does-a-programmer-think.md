---
description: >-
  Programmers need to break down problems into smaller pieces.  Then break those
  down into even small pieces.  This continues until the solution reveals
  itself.
---

# How Does a Programmer Think?

## Top Down Approach

Let's say you want to design a program that calculates how many days you've been alive based on a birth date provided and the current time.  There are a number of technical details to handle in a program like this.  So to avoid getting lost in those details, we start by thinking at the highest level. &#x20;

1. Ask the user for the birth date
2. Get the current date
3. Subtract them to get the number of days alive
4. Print the results

That's a high level design.  We have not addressed precisely HOW to ask the user for the information.  We have not resolved HOW to get today's date from the computer.  As we explore our design deeper, we sort out those details.  We continue to break things down into smaller tasks until we have a program that works.

* **Ask the user for the birth date**
  * Display a prompt for the birth date
  * Let the user enter the information
  * Check the information to make sure it's a valid date
  * Convert the birth date into a proper data type for use later on
  * If not, start over. &#x20;
* **Get the current date**
  * Use the TIME library and get the current date
* **Subtract them to get the number of days alive**
  * Subtract the birth date from the current date and get the difference
  * Calculate that difference into the number of days (secs \* minutes \* hours \* 24)
* **Print the results**

In the very beginning, the programmer might not know precisely how to perform each step.  The idea is to arrange the steps logically, break them down into smaller steps, and finally engineer the smaller steps.

We start at the highest level and then break things down into the detail level.   In our example above, it was a very simple program.  But imagine how complicated the design is for some of the software you use today.  Some of these systems, like Adobe Photoshop, took thousands of programmers years to create.

##### Some content generated with AI