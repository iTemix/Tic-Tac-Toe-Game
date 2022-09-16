
# TIC-TAC-TOE GAME

You probably already know how to play Tic-Tac-Toe. It's a really simple game, right? That's what most people think. But if you really wrap your brain around it, you'll discover that Tic-Tac-Toe isn't quite as simple as you think!

Tic-Tac -Toe (along with a lot of other games) involves looking ahead and trying to figure out what the person playing against you might do next.


## Screenshots
![](screenshots/Screenshot%20(16).png)
![](screenshots/Screenshot%20(17).png)
![](screenshots/Screenshot%20(19).png)
![](screenshots/Screenshot%20(20).png)


## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?
1. Array.from() lets you create Arrays from: 
- iterable objects (objects such as Map and Set); or, if the object is not iterable,
- array-like objects (objects with a length property and indexed elements).

2. document.getElementsByTagName('body')[0]:
- document.getElementsByTagName finds the elements that exist in the document as of when you call it that have that tag (body, head, p, a, div, etc.) So since you're calling it with the tag name "body", it finds all body elements in the document, if there are any when you call it.
- [0] then tries to get the first entry from the resulting list. If the list is empty, you get back undefined.
- So document.getElementsByTagName("body")[0] either gives you the first (and presumably only) body element in the document, or undefined if there is none (yet).

3. Switch (The dark and light mode)


## Acknowledgements

Special shout-out to all the developers in Dev Community, I'm glad to be a part of you guys. 
Thank you to Joshua Aubrey for literally forcing me to join this family. I hope to learn more and also contribute when needed, going forward.

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)

