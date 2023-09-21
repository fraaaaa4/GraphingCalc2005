# Graphing Calculator 2005
This is the repository of a Graphical Calculator I’m building as a side project. This project started mainly for two reasons: I wanted to learn on how to build apps using Visual Studio rather than Visual Basic (so therefore leraning more about C++ and C# also), and to see if I could use a particular product for development.
![image](https://github.com/fraaaaa4/GraphingCalc2005/assets/87281326/e7dd2783-4238-44d9-b295-099109f9b4bb)


## History
Some months ago, I wanted to get one of those little netbooks they were all the rage about in around 2007ish. Why? I never had one, and I've always found the idea of having such a small computer fascinating. I did look far and wide, but all the ones I looked at were either cheap or in very bad conditions. I'm talking stuff like the eee PCs, which were of doubtful quality even back in the day, or certain newer HP Minis, which not only were very pricey for what's essentially an extremely underpowered old device (40€ish), but they lacked the style and build quality.
One day, upon looking on all of these netbooks, I've found one which was perfect for my taste: big keyboard, silver finish (which no other netbook I saw had), aluminium frame, and premium build quality; it was the HP Mini 2133/2140, one either with a VIA chip, and the other with a good old Intel Atom CPU. I went on eBay to try and find one, to just have it, but to no avail, all the ones I did find were either damaged or very pricey, far more than what I'd have wanted to spend on this. That is, until, one day, I've found a listing for an untested, for parts, Mini 2140. I wasn't sure, but I ended up buying it anyway as it costed only 15€ - I figured out, if it didn't work, I could still sell it at a profit anyway.
Upon arrival, I've inspected it and was very dusty, both outside and inside - I had to take it apart, which was surprisingly very easy, and also a good surprise - turns out this laptop which was untested had actually all the parts in (including the original HDD, 1GB of RAM, and the battery). The only problem was some very light aesthetic damages, due to its age too. I cleaned it up, booted it up, and turns out all it needed was an OS to boot into. I did try firstly to install XP, as I thought it'd be the perfect choice; from there, I wanted to install 2002 but I failed. I so then went back to an era-appropriate OS, aka Vista - I know running it on an Atom wasn't the best idea, but I thought that, since this PC is from 2007, what better OS is there other than Vista? I did firstly install a debloated copy of Home Premium SP1, but nothing was working, so I decided to bite the bullet after a few months and I ended up reinstalling Vista Ultimate SP2.
Some months pass, and I start installing stuff on this - Minecraft Alpha, ClassiCube, mypal, configure the mail, calendar, contacts, Visual Studio, Java, etc.. Turns out, this netbook, for as crappy as it is, is an excellent writing machine thanks to its absolutely gorgeous keyboard (it's just so nice to type on). I wanted to push it a bit more though: what if I could run an older version of VS on it? I started out with Visual C++ 6.0, since i figured out that would've been old enough to run without problems. Upon opening it tho, I was just - completely lost, I didn't know where to get the designer view, how to even start making an app in it, so I decided to scrap it and move to a .NET based environment. I've chosen VS2005 because VS.NET was too old and didn't include many features which would be handy, and I figured out that VS2010 might've been too much heavy. Plus, in VS2005 you can develop also for Windows Mobile, and is fairly lightweight. I've gotten the opportunity of this challenge to also learn a bit more about C++ and C#, since for now I've just done VB and Java.

![image](https://github.com/fraaaaa4/GraphingCalc2005/assets/87281326/bd910d42-ec51-4491-8b6f-bb76e7ec743c)

Surprisingly enough, it's more than decent to work on this project on this Atom! Sure, sometimes when just booted up, the hard disk might chug a bit to load all the project files, but once it loaded everything (which takes surprisingly little), the only thing that's annoying is the screen space, nothing that could be fixed if I were to plug in it a bigger monitor probably.
The development environment is very different from what you're used to today with VSCode and the others, but for me it's right at home - I've had some experience in the past with VB6 and VB2010, and this was exactly the same. I've also adapted pretty quickly to C#, learning that it's just like Java, but with minor changes - this code language is extremely developer friendly and easy to understand. The taskbar is on the left side and not right side to save some vertical space ;)
![image](https://github.com/fraaaaa4/GraphingCalc2005/assets/87281326/50b3c99d-17e8-40d6-84d6-f6020b7143a3)

## Features
This Graphing Calculator is currently in **Alpha**, which means that the basic features are already here. Here is a quick overview:
- **Legacy Graphs**: this feature will be deprecated once it becomes Beta; it draws a few basic curves (sin, cosin, tan) based on a hard-coded function. Takes an x and y value.
- **Expression-based Graphs**: this method is the new one, and is the one which will be used during development. Given an x value (you have to set it up from which x value you want to go from, and to which x value you want to go to), by using a math parser the program calculates the y value of the function (result); the x and y values of these calculations are then passed as a list to the graph, which will proceed to paint all the points in the respective coordinates.
- **User-defined variables**: if you want to insert inside your expression multiple variables with custom names/variables, the parser will be able to recognise them
- **Precision**: this lets you control how many times the program must evaluate the expression given basically. The higher the value is, the less precise the curve will be. The lower the value is, the more precise the curve will be; bear in mind that, if you give too low values, on certain computers, drawing a graph can take even up to 15 minutes.
- **Axis**: you can change the data source of the assets (e.g. you want to have some text instead of numbers). You can also customise the scale of each axis, and disable/enable the labels.
- **Titles**: you can add titles to your curves, to your graph, and to your axis too.
- **Colours**: as seen from the demonstration picture, you can: colour your line, colour the inside of each point (with gradients), colour the base of each line (with gradients), colour the inside and outside of the graph.

There are also some graph-specific functions, such as:
- **Copy the graph**
- **Print the graph**
- **Save the graph** as a picture
- **Zoom in/out** in the graph, to get a more detailed look at your curve
- **Get detailed x/y values**, both in a list view or by moving your mouse pointer upon the chosen point
- **Add a gridline to the graph** to make it easier to read.

## Compatibility
I haven't tested compatibility yet, but it should work on Windows 2000+ without any problem. Remember that you need .NET Framework in order to run this.

In the next days the source code and the first build will be available.
