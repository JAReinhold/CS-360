# CS-360
Repo for my CS-360 course at SNHU

This ReadMe is a brief discussion of my inventory management app dubbed "MisManaged"

For this project, the goal was to build a functional Android app that uses a persistent database, user login, and basic notifications. The app I created, MisManaged, is a simple inventory tracker where users can create an account, log in, add items, update quantities, delete items, and optionally receive SMS alerts when stock gets low. The main focus was making something straightforward and easy to use instead of overly complex.

The app needed a few main screens to support the user. A login screen handles account creation and sign-in, the inventory screen shows items in a grid so they are easy to manage, and a notification screen allows the user to enable or disable SMS alerts. I tried to keep the UI simple and consistent so the user always knows what to do and can move between screens without confusion.

When coding, I worked step by step instead of doing everything at once. I built the UI first, then the database, then login, and finally permissions and notifications. Keeping the code separated into different classes helped keep things organized and made debugging easier. This is a process I would use again in future projects.

Testing was done often using the Android emulator to make sure login worked, the database saved correctly, items could be changed, and the app still ran if permissions were denied. This helped catch problems early and made the app more stable.

One challenge was handling permissions for SMS alerts without breaking the rest of the app. The app had to keep working even if the user denied permission, which required extra checks in the code. The part I was most successful with was the database and inventory system, since it connects the UI, storage, and user actions together and makes the app feel like a real product.
