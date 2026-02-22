# CS-360-Mobile-Architect-Programming

CS 360 Portfolio Artifact 

My Reflection

For this course, I built a mobile inventory app. The goal was simple. I wanted users to be able to log in, add items, track quantities, and update their inventory without confusion. The app was designed for someone who needs a quick way to manage items and know when supplies are running low.

The main screens included a login screen, an inventory list screen, and screens to add or edit items. The inventory screen shows items in a clean grid so users can see everything at once. The add and edit screens use clear labels and simple input fields. I avoided clutter and kept navigation simple. I also made sure the app still works if the user denies SMS permissions. That was important because the app should not break just because a permission is turned off.

When I started coding, I worked step by step. I did not try to build everything at once. First, I made sure the login worked. Then I set up the database. After that, I connected the UI to the stored data. I tested each feature before moving on. If something failed, I fixed it before adding new code. This made the project easier to manage. I also reused code when possible instead of rewriting the same logic in different places.

I tested the app using the Android Emulator. I tried normal actions, like adding and editing items. I also tested edge cases. I left fields blank. I entered incorrect data. I denied SMS permissions. This helped me catch problems early. Testing showed me that permission handling needed extra checks to avoid crashes. Without testing, I would not have caught that.

One challenge was handling SMS permissions correctly. I had to make sure the app asked at the right time and responded correctly if the user said no. That required extra logic and repeated testing. Solving that problem improved my understanding of how mobile apps interact with device features.

The part I am most proud of is how the inventory list connects directly to the database. When a user adds or updates an item, the change appears right away. That showed me I can connect the front end and back end successfully.

This project helped me understand the full development cycle. I learned how to plan, design, code, test, and prepare an app for launch. It gave me a complete project that I can include in my portfolio and talk about in interviews.
