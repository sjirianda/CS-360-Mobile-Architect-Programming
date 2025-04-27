# CS-360-Mobile-Architect-Programming
## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The app needed a traditional log-in system for creating and accessing accounts, SMS notifications, and permission request dialogs. It was designed to let users log their daily weight, view their weight history, edit or delete entries, and get notified when they reach their weight goal.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The app included a log-in screen and a weight tracking screen. The log-in screen followed familiar designs users are used to, making it easy and intuitive. By using familiar workflows, the UI felt natural and user-friendly, leading to a successful design.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
I used Design Driven Development (DDD), starting by designing static UI layouts first, then adding functionality. For dynamic elements like weight entries, I used a RecyclerView instead. This approach can be reused in future apps for static components and adjusted for dynamic content.

## How did you test to ensure your code was functional? Why is this process important and what did it reveal?
I tested mainly through informal code reviews and debugging. This helped catch logic errors like inverted if-else conditions and race conditions with DialogFragments. Testing was critical to fix bugs that would have broken key app features.

## Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
I had to innovate while building the daily weight list. Instead of a complicated dynamic GridLayout, I used a RecyclerView with GridLayout entries. This avoided needing a custom scrollbar and made the app smoother and easier to manage.

## In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I showed my skills best in the log-in screen and Room database. The log-in screen demonstrated my ability to connect XML layouts with Java code. The Room database showed my understanding of SQL queries, data management, and use of annotations with external libraries.
