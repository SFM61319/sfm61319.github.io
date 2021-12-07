### Hi there 👋! I am Avinash ([SFM61319](https://github.com/SFM61319 "SFM61319")), a curious programmer from India!

Like the `h3` header above says, My name is Avinash, I am 18 years old. And I am one curious and interesting programmer. I have been programming (not [just] scripting) since I was around 10 years old (one can say I have over 8 years of experience, unofficially).  
  
It all started when I was first taught HTML (officially), along with some CSS and JavaScript (unofficially taught by my teacher, yes she was a cool teacher 😎) from class 6 to 8 - I know, HTML and CSS aren't *programming* but *markup* and *styling* languages respectively, but JavaScript is (isn't it?) - which piqued my interest in programming. I learnt them as much as I could till class 8, after which in class 9 and 10, I started learning C and C++ on my own.  
  
C++ was what I used to learn and understand Object-Oriented Programming too (and can easily and efficiently implement different Data Structures using classes (with generics too), and write efficient algorithms to process the data held in those structures, all using just the C++ STL). And thanks to C++, and how performant it can be and how much of an optimised code we can write in it, I dug deeper on system architecture and other hardware level stuff and learnt and understood a bit about hardware-level optimizations and how C++ achieves them --  
For example, how a small [`std::vector`](https://en.cppreference.com/w/cpp/container/vector "C++ Vector") is generally faster than a small [`std::list`](https://en.cppreference.com/w/cpp/container/list "C++ Linear Doubly Linked List") - even for mid-collection insertions and deletions - because of:  

+ A vector being array-ish (contiguous blocks of memory, constant-time access of elements just by indices)
+ Indirections being slow (since pointers are used in linked lists)
+ Possible allocation of said vector in CPU data cache and local registers (remember, we are comparing **small** vectors with **small** lists, and smaller things may fit in the cache and registers depending on the CPU) for faster access - part of hardware optimization - by the CPU, which also makes shifting of elements for mid-collection insertions/deletions faster than de-referencing of pointers in memory
+ CPU Branch Prediction - again, part of hardware optimization, being ahead by predicting the next 15 to 20 actions based on the past action(s), hence knowing what to do and being faster - which works for contiguous blocks of memory of the same data type, but not for random pointers pointing to different memory locations - which have to be de-referenced first - causing CPU misprediction (pointer indirection being responsible again)

-- Apart from it already being faster than most languages because of it being compiled, statically typed, and it's ability to compile to native bytecode.  
  
Then in class 11 and 12, I chose Computer Science (over Physical Education), in which I was taught about computers, operating systems, different types of languages (and their categories and sub-categories), and mainly, Python 3 and MySQL.  
Python being so simple, readable, and hence easy (while less performant, quite the opposite of C++ in most aspects), quickly became one of my favorite languages (the other favorites being, C++ (my favorite-est language) and C# - I'll come to C# in a few ~~seconds~~ I mean words). I do everyday basic automation in Python whenever possible, and write (what I find to be) useful Python libraries (though I may never publish them to [PyPI](https://pypi.org/ "Python Package Index")), and Machine Learning, Deep Learning and Artifical Intelligence projects. Apart from Python 3, I also learnt C# on my own in class 11 and 12. And C# is, in my humble opinion, Java, but good (I actually once wrote a thirty-pointer on why C# is much better than Java). It's just too good. And then, knowing JavaScript and C#, I learnt TypeScript. It's the perfect blend of JavaScript and C#.  
  
And as of now, I can write vanilla HTML, CSS, and JS, or ReactJS/TS frontend websites, with Django (Python), Node.js (using the `express.js` library), or ASP.NET (Core) backend, with MySQL, SQL, MongoDB or PostgreSQL databases. I can also write modern Windows desktop apps ([WPF](https://docs.microsoft.com/en-us/dotnet/desktop/wpf/?view=netdesktop-6.0 "Windows Presentation Foundation") or [UWP](https://docs.microsoft.com/en-us/windows/uwp/ "Universal Windows Platform")) in C# (with XAML) and/or C++. And I can quickly write simple Tkinter apps in Python. I can write all these projects with proper version control using [Git](https://git-scm.com/ "Git SCM").  
  
And finally coming to the favorites in the meta part, my favorite code editor is Visual Studio Code (although I use vim 8.2 - and I like vim too - on Arch Linux ARM on my Android phone, and compile and run code using compilers like GCC, G++, Mono C#, and interpreters like Node.js and Python 3 for Arch Linux ARM, due to "hardware insufficiencies"), and IDE is Visual Studio 2022 (it was Visual Studio 2019 until Visual Studio 2022 was released).  
  
To sum it all up, I'm an enthusiastic and a curious learner and a programmer who absolutely *loves* programming. And a little known secret, I took up CSE not because of the pay or the job opportunities, but because I *love* programming. I want to work for Google and Microsoft one day, especially the Google search engine, Android OS, Material UI (now Material You), and the Google Assistant areas in Google, and Windows 11, [WinUI](https://docs.microsoft.com/en-us/windows/apps/winui/ "Windows UI"), [Fluent UI](https://developer.microsoft.com/en-us/fluentui#/get-started/web#fluent-ui-react "Fluent UI React"), and a few more areas in Microsoft.  
  
So basically, I'm proficient in:
+ C
+ **C++**
+ **Python**
+ JavaScript
+ C#
+ TypeScript
+ SQL
+ MySQL
  
And can make projects using:
+ ReactJS/TS
+ Express.js
+ Django
+ ASP.NET (Core)
+ SQL
  
And I wrote a few projects like I said above, some huge. And I'll be working on their much modern remakes soon. Projects like:
+ [DyePy](https://sfm61319.github.io/DyePy "DyePy - A colorful library") - A color library in Python
+ [dsalgos](https://sfm61319.github.io/dsalgos "DSAlgos - A Data Structures and Algorithms library") [*unpublished*] - A Data Structures and Algorithms library in Python (will possibly be remade with Python 3.10 compatibility and features, if not in C/C++ (Python extended in C))
+ Spidey [*unpublished*] - A Discord bot written in discord.js v12 (will be remade in Node.js v17+, discord.js v13+)
+ color++ [*deleted for remake*] - An efficient color library in C++ (to be remade in newer C++ standards with optimizations and more and better features)
+ ColorSharp [*deleted for remake*] - An efficient color library in C# (to be remade efficiently in the latest stable C# and .NET versions)
+ dsalgos++ [*deleted for remake*] - An efficient Data Structures and Algorithms library in C++ (to be remade in newer C++ standards with optimizations and better interfaces and features, possibly with custom user structure and algorithm extensibility)
+ Material [*deleted for remake*] - A UWP app to play around with WinUI materials like [Acrylic](https://docs.microsoft.com/en-us/windows/apps/design/style/acrylic "Acrylic Brush") and Reveal (discontinued, main reason for proper Windows 11 compatible remake)
+ Ruqqus Windows [*deleted*] - A UWP app for Ruqqus (development discontinued and project deleted after discontinuation of Ruqqus due to moral issues on their site)
+ FluentUI [*deleted*] - A vanilla HTML, CSS and JavaScript UI library to use WinUI components on the web (deleted after encountering [Fluent UI React](https://developer.microsoft.com/en-us/fluentui#/get-started/web#fluent-ui-react "Fluent UI React"), an up-to-date ReactJS/TS alternative. Now contributing to Fluent UI React)
  
Well, this (hopefully) explained about the programmer in me in a little over 5 minutes.  
  
```cpp
#include <iostream>

int main()
{
    std::cout << "Thanks for reading!\n";
    return EXIT_SUCCESS;
}
```
  
Oh by the way, some of my repositories have their own GitHub pages (under this domain), be sure to check them out!
