# Mobile-Architecture-and-Programming
My final project for the CS-360 Mobile Architect &amp; Programming class

# What is it?
My project is an android mobile app called Weight Track. Weight Track is a very simple application that helps the user track their weight loss journey over time by entering daily weights. The user sets a weight goal for themselves and then records their weight each day to watch their progress over time. When the user reaches their goal, they will be texted a congratulatory message. The app allows the user to create, edit, read and delete daily weight entries in a pleasant and simple UI.

# How does it work?
The app is built primarily around the CRUD model (Create Read Update and Delete) and allows the user to interface with two different SQLite databases. The app keeps all the information stored between a database of accounts and a database of weight entries, both of which are linked by an id value. The IDs are unique to each account and generated on creation, and the weight entries for each account are connected to them by using that same id as a value in the weight table. The UI of the app is built to facilitate the viewing of the weight database as much as possible, with as little complexity as possible. The first screen is a login screen, so the user's ID can be acquired. Once they're logged in, they're taken to the main screen, where the weights for the account's ID are displayed in a scroll view and different buttons are present for the different CRUD functionalities. There's also an area to set the weight goal for the account, and a button to permit the app to text the user congratulations when they hit their goal. This permission can easily be turned down without sacrificing any of the app's core functionality.

# How was the programming process?
Weight Track was both incredibly difficult and yet extremely fun to do. It was hard to piece together all the elements I needed, be it new plugins or structures like the databases, or more physical UI elements like the theming. The UI is very important to mobile programming due to the limited space, and I had to keep the visuals in mind whenever I created something. But, I feel like that struggle helped me organize both the code and the visuals better in the end. I used a lot of visuals in my testing, having toasts that stated unseen tasks or just checking the layout with a variety of normal and edge cases to see how it affected the app in real-time. Looking back at it, I feel like the main screen did end up cluttered, and with some better design knowledge, I could make it look a lot more pleasing. I'm happy with the colors though: green is a color of growth, and it’s supposed to represent the growth the user is going through in their weight loss journey. On the programming side, I'm proud of how it turned out. I feel like using two SQLite databases turned out to be a massive success, as it made my code and my data much more organized than squishing everything into one would have been. I enjoyed working with Android Studio and mobile development, and I'd be down to explore mobile development as a future career.
