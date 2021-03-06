Welcome to the Reactive Extensions (Rx) Koans
=============================================

"Learn by Doing"
55 progressive examples to help you learn Rx
By: Bart De Smet & Llewellyn Falco

The original project was based on MSTest, I have ported it to XUnit because MSTest is just too painfully slow to use.
http://rxkoans.codeplex.com/

Definition of ‘Koan’
--------------------
Kōans is a zen word meaning the enlightenment or awakening of a person, usually through a puzzle or riddle. The most common one is “What is the sound of one hand clapping?”

What is this all about?
-----------------------
Rx is a new innovative way to work with asynchronous operations on event streams. It is composable, and uses well-known LINQ syntax to easily express complex timing and event processing operations. 
This RxKoans are an interactive and fun way to be introduced to and learn Rx.

Current Lessons
===============
Lesson0Lambdas
Lesson1ObservableStreams.cs
Lesson2ComposableObservations.cs
Lesson3Linq.cs
Lesson4Time.cs
Lesson5Events.cs
Lesson6AdvancedStreams.cs
Lesson7AsyncInvoke.cs

Getting Started
---------------
Open the Visual Studio 2010 Solution, and open the file Koans\Lessons\Lesson1ObservableStreams.cs
Press Ctrl R, T (not Ctrl R, Ctrl T). Fill in the blank (____) Run it again to see it pass.
After you finish Lesson1, move to the other LessonX files.

Running Koans
-------------
Ctrl R, T will run the koans. It will run either the single koan your cursor is on, or the whole file, if your cursor is not in a specific koan (Unit Test).
Running in Debug Mode:
Ctrl R, Ctrl T will run in Debug mode, we do not suggest this, as it just makes things slower and more confusing.


Tips & Tricks
-------------
Play: Experimentation is a powerful learning tool. Don't be afraid to try stuff out, and run it to see what happens.
Run the Test: It is valuable to see what the results are. All Koans are designed to produce something even before they are filled in.
Debug: Set some break point and walk thru the code. It's a great way to get details. (Ctrl+R, Ctrl+T) will run in debug mode.
Do Them with a Friend: Learn is more fun and less fustrating when you have a friend with you.

Links:
------
Rx : http://msdn.microsoft.com/data/gg577609
Javascript Rx Koans: https://github.com/panesofglass/RxJSKoans/network
Original project: http://rxkoans.codeplex.com/
