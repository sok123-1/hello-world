
# 📱Habitly

---
## Notes
To sign in create an account or use the premade account - 
Email - mrclark@gmail.com
Password - Mrclark
The sign in page can be buggy at times, the demo page can break.


## Some code from this project has been outsourced and the links for the original projects have been provided below - 

https://www.figma.com/make/GbVcdsC9BKSWZlj3odjOgw/Habit-Tracking-App?node-id=0-1&p=f&t=AeEPpwhu9AHEECch-0
https://github.com/Hebert-code/habitrack?tab=readme-ov-file
https://github.com/LuuNgocLan/flutter-habit-tracker?
https://github.com/topics/habit-tracker?
Inbuilt co pilot in vs code 

Test it on google chrome for better formatting

## Instrucions for the users

Extract the files from the other linked github repository
Set up flask environment in Vs code
Ensure you have all neccessary extensions installed 
Run python main.py in terminal
Follow the link to the website

##  What is Habitly?

**Habitly** is an App where you can create habit lists, set goals and join leaderboards with your friends to compete to see who can keep their habit streak for the longest.
---

##  Functional Requirements

- Track daily, weekly, and monthly streaks
- Create or join groups to compare streaks and habit goals
- View leaderboards and group streaks
---

##  Non-Functional Requirements

- Responsive and intuitive user interface
- Data privacy and security for all users
- Scalable to support many users and groups

## Basic Wireframe Sketches

![computing wireframe-min](https://github.com/user-attachments/assets/38c35426-8583-4b02-af86-30e9482c4a15)\

<img width="3024" height="4032" alt="image" src="https://github.com/user-attachments/assets/92e9fa69-2505-4ea3-9e99-cbf8a0fb3ee6" />

![image-min](https://github.com/user-attachments/assets/9b32f4b0-1d5f-4478-ad4c-8c15764703ab)

---

## Figma Wireframe Sketches

<img width="616" height="763" alt="image" src="https://github.com/user-attachments/assets/13a7a708-636e-4cf1-8973-bde0abd75eeb" />

<img width="625" height="740" alt="image" src="https://github.com/user-attachments/assets/fd4ad8b3-9b76-4949-9306-4a4e328dfcc8" />

<img width="721" height="827" alt="image" src="https://github.com/user-attachments/assets/0f3c8513-456c-4e91-bc4d-cb32d2c4f4d1" />

---

## Algorithm test cases

<img width="503" height="853" alt="image" src="https://github.com/user-attachments/assets/adf9d5a9-528d-4528-83ac-cd10cc455cdd" />

**Test case 001**

Test case id: TC001

Precondition: User is logged in and on "Add habit" page

Test steps
1. Leave habit name blank
2. Select frequency = Weekly
3. Select start date =  Valid start date
4. Save

Expected Results: System shows habit error message "Habit name required" and does not save the habit, redirecting user to add habit screen.

**Test case 002**

Test case id: TC002

Precondition: User is logged in and on "Add habit" page

Test steps
1. Enter habit name = "Drink water"
2. Select frequency = Daily
3. Select start date = Valid start date
4. Click save

Expected results : System saves habit successfully and displays "Habit successfully added" and redirects user to add habit screen.

**Week 7**

- Using figmas generated code for my website and also using the inbuilt copilot in vs code to insert the code I created my pages.
- Added a sign in page, which was there for aesthetic purposes however was not functional just yet.
- Added a habits tracker, you can add and remove habits however it was not fully functional and convenient for the user


**Week 8**

- Worked on the colour scheme initially wanted a blue and white colour scheme but decided to go for a teal colour palette with brown coloured highlights.
- Tried to get the sign in page functional however it did not work
- Worked on the habit list made sure you could edit habits and the streak counter is accurate

**Week 9**

- Added an sql database so habits don't disappear once you leave the habits page.
- Worked on the stats page, and diary entries which is still a work in progress

**Week 10**

- Made sure that the interactivity worked between pages and continued working on diary entries, added a filter for different types of diary entries
- Continued working on the stats page, and added habit groups which are filters for your different habit groups which you can easily filter through
- Used copilot's built in software to help me fix a bug I had with all the animations in my app

  **Week 1 T4**

- Focused on changing the layout a bit to make it more user friendly
- finally fixed the sign in page so that everyone has their own private account
- Final touch ups

**Lighthouse Test**

Sign in Page

<img width="1900" height="988" alt="image" src="https://github.com/user-attachments/assets/38de3305-7dd0-4f5a-9950-79340e01d28c" />

Home Page

<img width="1908" height="983" alt="image" src="https://github.com/user-attachments/assets/7ea0cf4f-6ddc-4366-b410-5829d07b94e7" />

Stats Page

<img width="1916" height="972" alt="image" src="https://github.com/user-attachments/assets/caf5264f-7731-4b19-b21e-4663d394e4de" />













