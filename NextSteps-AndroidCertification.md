# Next Steps - Android Certification

## Becoming an Android Dev
* [Mistakes I made (as a developer)](https://medium.com/@Miqubel/mistakes-i-made-d2e1dc4e820a) (Nov 6, 2016) by [Miquel Beltran](https://medium.com/@Miqubel) - I started working in 2006, a decade ago. Such milestone inspired me to look back and point at the mistakes I did, and the kind of advice I wished someone from the profession had told me. Things change fast, I am not sure how applicable this tips will be in ten years. Either if you just started or you are a grey-beard, you might find my words helpful. I would love to hear your opinion, so don’t hesitate to write me.
* [How to Break into a Mobile Dev Career in 10 months or less](https://www.philosophicalhacker.com/2014/05/22/how-to-break-into-a-mobile-dev-career-in-10-months-or-less/) (May 22, 2014) - At this point, I think its safe to say that I have successfully broken into a mobile dev career with a master’s degree in a philosophy. What follows is a combination of programming resources and advice that helped me pull this off. I’m hoping that other non-traditional hackers like me will find these resources useful.


## Android Developer Certification
[Introducing Associate Android Developer Certification by Google](https://android-developers.googleblog.com/2017/02/introducing-associate-android-developer.html)

The Associate Android Developer Certification program was [announced at Google I/O 2016](https://www.youtube.com/watch?v=Yu2oGere_Mc), and launched a few months later. Since then, over 322 Android developers spanning 61 countries have proven their competency and earned the title of Google Certified Associate Android Developer. 

To establish a professional standard for what it means to be an Associate Android developer in the current job market, Google created this certification, which allows us to recognize developers who have proven themselves to uphold that standard.

The certification process consists of **a performance-based exam** and **an exit interview**. The certification fee includes **three exam attempts**. The **cost** for certification is **$149 USD**, or 6500 INR if you reside in India. After payment, the exam will be available for download, and you have **48 hours** to **complete** and **submit** it for grading.

In the exam, you will implement missing features and debug an Android app using [Android Studio](https://developer.android.com/studio/intro/index.html). If you pass, you will undergo an exit interview where, you will answer questions about your exam and demonstrate your knowledge of [Associate Android Developer competencies](https://www.udacity.com/google-certifications#exam-details).

When you are ready to start, you will [sign up](https://www.udacity.com/google-certifications) and pay to take the exam. You have 48 hours from the time you receive your exam until the time you must submit it. If you do not submit your exam within 48 hours, your attempt will count as "failed" and you will need to take another exam to proceed with the certification process.

If a candidate does not pass the Certification exam, they may retake it in the following manner:

* If a candidate does not pass their first attempt, they may immediately retake the exam.
* If a candidate does not pass their second attempt, they will be eligible for their third attempt after a two month period.
* If after three attempts, the candidate has still not passed the exam, they must wait six months. After six months, if the candidate still wishes to take the exam, they must pay for the exam to take it again.


## Associate Android Developer Exam
[Associate Android Developer Exam](https://www.udacity.com/google-certifications) by [Udacity](https://www.udacity.com/)

### What does the exam cover?

The Associate Android Developer Exam will ask you to demonstrate skills in the following areas:

#### Testing and Debugging
Writing tests to verify that the application's logic and user interface are performing as expected, and executing those tests using the developer tools. Candidates should be able to analyze application crashes, and find common bugs such as layout errors and memory leaks. This includes working with the debuggers to step through application code and verify expected behavior.

* Write and execute a local JVM unit test
* Write and execute a device UI test
* Given a problem description, replicate the failure
* Use the system log to output debug information
* Debug and fix an application crash (uncaught exception)
* Debug and fix an activity lifecycle issue
* Debug and fix an issue binding data to views


#### Application User Interface (UI) and User Experience (UX)
Implementation of the visual and navigational components of an application's design. This includes constructing layouts–using both XML and Java code–that consist of the standard framework UI elements as well as custom views. Candidates should have a working knowledge of using view styles and theme attributes to apply a consistent look and feel across an entire application. Understanding of how to include features that expand the application's audience through accessibility and localization may also be required.

* Mock up the main screens and navigation flow of the application
* Describe interactions between UI, background task, and data persistence
* Construct a layout using XML or Java code
* Create a custom view class and add it to a layout
* Implement a custom application theme
* Apply a custom style to a group of common widgets
* Define a RecyclerView item list
* Bind local data to a RecyclerView list
* Implement menu-based or drawer navigation
* Localize the application's UI text into one other language
* Apply content descriptions to views for accessibility
* Add accessibility hooks to a custom view


#### Fundamental Application Components
Understanding of Android's top-level application components (Activity, Service, Broadcast Receiver, Content Provider) and the lifecycle associated with each one. Candidates should be able to describe the types of application logic that would be best suited for each component, and whether that component is executing in the foreground or in the background. This includes strategies for determining how and when to execute background work.

* Describe an application's key functional and nonfunctional requirements
* Create an Activity that displays a layout resource
* Fetch local data from disk using a Loader on a background thread
* Propagate data changes through a Loader to the UI
* Schedule a time-sensitive task using alarms
* Schedule a background task using JobScheduler
* Execute a background task inside of a Service
* Implement non-standard task stack navigation (deep links)
* Integrate code from an external support library


#### Persistent Data Storage
Determining appropriate use cases for local persisted data, and designing solutions to implement data storage using files, preferences, and databases. This includes implementing strategies for bundling static data with applications, caching data from remote sources, and managing user-generated private data. Candidates should also be able to describe platform features that allow applications to store data securely and share that data with other applications in a secure manner.

* Define a database schema; include tables, fields, and indices
* Create an application-private database file
* Construct database queries returning single results
* Construct database queries returning multiple results
* Insert new items into a database
* Update or delete existing items in a database
* Expose a database to other applications via Content Provider
* Read and parse raw resources or asset files
* Create persistent preference data from user input
* Toggle application logic based on preference values


#### Enhanced System Integration
Extending applications to integrate with interfaces outside the core application experience through notifications and app widgets. This includes displaying information to the user through these elements and keeping that information up to date. Candidates should also understand how to provide proper navigation from these external interfaces into the application's main task, including appropriate handling of deep links.

* Create an app widget that displays on the device home screen
* Implement a task to update the app widget periodically
* Create and display a notification to the user

