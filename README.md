# DontStepOnTheCrack

Don't step on the crack was a game that I made for my CS 108 Game Studies class that I took during college in the semester of Spring 2014. It was made in GameMaker, which required me to code the features of the character/boss/etc but could handle some of the simpler stuff with a UI. I worked with my partner David, who provided the art. The basic premise of the game is to jump over and move around cracks on the sidewalk until you get to the boss, where you can punch, kick, and combo for special moves in order to defeat him. There are 3 levels and the game gets faster and the bosses get harder at each stage. Beat the final boss and you beat the game! Here are the blog posts from that semester where I described the process of making the game:


-Don't step on the crack blog-
I started making the first draft of the game in GameMaker. So far it's just a guy walking on a sidewalk.  David provided the art and I implemented the programming. The challenging part was getting the character to stay within the bounds of the sidewalk. It seemed like a simple pixel boundary implementation but I had to figure out a way to let the character go past that boundary when jumping.
![Initial Art](https://jihooncs108.files.wordpress.com/2014/03/untitled-11.jpg)

Next I added the background of the trees and houses, which would pass by more slowly than the sidewalk creating a paralax effect. Adding the cracks was next, and I made them randomly generated from off the screen so the game would be more challenging. A challenge here was that for some reason it wasn't really random. It was showing the same pattern every time. I fixed this by adding code that would simulate true randomness on every run. I also implemented a random background, where different color houses and trees would show up and pass by in the background. Next were the health bar, which goes down by a certain amount on hitting the cracks, and the distance meter, which goes up at a constant rate.
![](https://jihooncs108.files.wordpress.com/2014/03/untitled-2.jpg)

We decided after that that we should implement more levels. We decided on 3 levels. David sent me more art to work with such as the level screens and a new start/end screen.
![](https://jihooncs108.files.wordpress.com/2014/04/title-screen.png)
![](https://jihooncs108.files.wordpress.com/2014/04/gameoverscreen.png)

I then added new challenges. The first was a dog that would come up from the left side of the screen and force you to play more on the right side and react faster to the cracks, making it harder to dodge them. I used a timer to have a dog run in from the left fast at the start and then slow down and stop at a certain point on the screen, and then follow the player’s x axis (up and down). If the player made contact with the dog, game over. We also added a boss at the end of the level that used the fight mechanics (punch, block, kick). I had some trouble with the punch/kick repeating really fast if I held down the button, but I fixed that by making them take a certain amount of time to complete. After that, we added music for the cracks part and separate music for the boss. Then, sound effects for the jumping and getting injured.
![](https://jihooncs108.files.wordpress.com/2014/04/temp1.jpg)
![](https://jihooncs108.files.wordpress.com/2014/04/temp1.jpg)
We decided after that that we should implement more levels. We decided on 3 levels. David sent me more art to work with such as the level screens and a new start/end screen.
![](https://jihooncs108.files.wordpress.com/2014/04/title-screen.png)
![](https://jihooncs108.files.wordpress.com/2014/04/gameoverscreen.png)

I then added new challenges. The first was a dog that would come up from the left side of the screen and force you to play more on the right side and react faster to the cracks, making it harder to dodge them. I used a timer to have a dog run in from the left fast at the start and then slow down and stop at a certain point on the screen, and then follow the player’s x axis (up and down). If the player made contact with the dog, game over. We also added a boss at the end of the level that used the fight mechanics (punch, block, kick). I had some trouble with the punch/kick repeating really fast if I held down the button, but I fixed that by making them take a certain amount of time to complete. After that, we added music for the cracks part and separate music for the boss. Then, sound effects for the jumping and getting injured.
![](https://jihooncs108.files.wordpress.com/2014/04/temp1.jpg)
![](https://jihooncs108.files.wordpress.com/2014/04/temp1.jpg)
