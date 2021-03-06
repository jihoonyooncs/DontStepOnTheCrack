# DontStepOnTheCrack

Don't step on the crack was a game that I made for my CS 108 Game Studies class that I took during college in the semester of Spring 2014. It was made in GameMaker, which required me to code the features of the character/boss/etc but could handle some of the simpler stuff with a UI. I worked with my partner David, who provided the art. The basic premise of the game is to jump over and move around cracks on the sidewalk until you get to the boss, where you can punch, kick, and combo for special moves in order to defeat him. There are 3 levels and the game gets faster and the bosses get harder at each stage. Beat the final boss and you beat the game. Unfortunately as it has been a while since I made it I do not have the code/program files anymore. 

##How to Run the Game
Simply download the exe file and run it on your computer.

##Blog
Here are the blog posts from the semester when I made the game. I describe the process as well as the features.

-Don't step on the crack blog-
I started making the first draft of the game in GameMaker. So far it's just a guy walking on a sidewalk.  David provided the art and I implemented the programming. The challenging part was getting the character to stay within the bounds of the sidewalk. It seemed like a simple pixel boundary implementation but I had to figure out a way to let the character go past that boundary when jumping.

<img src="https://jihooncs108.files.wordpress.com/2014/03/untitled-11.jpg" width="500">

Next I added the background of the trees and houses, which would pass by more slowly than the sidewalk creating a paralax effect. Adding the cracks was next, and I made them randomly generated from off the screen so the game would be more challenging. A challenge here was that for some reason it wasn't really random. It was showing the same pattern every time. I fixed this by adding code that would simulate true randomness on every run. I also implemented a random background, where different color houses and trees would show up and pass by in the background. Next were the health bar, which goes down by a certain amount on hitting the cracks, and the distance meter, which goes up at a constant rate.
<img src="https://jihooncs108.files.wordpress.com/2014/03/untitled-2.jpg" width="500">

I then added new challenges. The first was a dog that would come up from the left side of the screen and force you to play more on the right side and react faster to the cracks, making it harder to dodge them. I used a timer to have a dog run in from the left fast at the start and then slow down and stop at a certain point on the screen, and then follow the player’s x axis (up and down). If the player made contact with the dog, game over. We also added a boss at the end of the level that used the fight mechanics (punch, block, kick). I had some trouble with the punch/kick repeating really fast if I held down the button, but I fixed that by making them take a certain amount of time to complete. After that, we added music for the cracks part and separate music for the boss. Then, sound effects for the jumping and getting injured.

<img src="https://jihooncs108.files.wordpress.com/2014/04/temp1.jpg" width="500">
<img src="https://jihooncs108.files.wordpress.com/2014/04/temp1.jpg" width="500">

We decided after that that we should implement more levels. We decided on 3 levels. David sent me more art to work with such as the level screens and a new start/end screen.

<img src="https://jihooncs108.files.wordpress.com/2014/04/title-screen.png" width="500">
<img src="https://jihooncs108.files.wordpress.com/2014/04/gameoverscreen.png" width="500">

I then added new challenges. The first was a dog that would come up from the left side of the screen and force you to play more on the right side and react faster to the cracks, making it harder to dodge them. I used a timer to have a dog run in from the left fast at the start and then slow down and stop at a certain point on the screen, and then follow the player’s x axis (up and down). If the player made contact with the dog, game over. We also added a boss at the end of the level that used the fight mechanics (punch, block, kick). I had some trouble with the punch/kick repeating really fast if I held down the button, but I fixed that by making them take a certain amount of time to complete. After that, we added music for the cracks part and separate music for the boss. Then, sound effects for the jumping and getting injured.

<img src="https://jihooncs108.files.wordpress.com/2014/04/temp1.jpg" width="500">
<img src="https://jihooncs108.files.wordpress.com/2014/04/temp1.jpg" width="500">

For the initial prototype of the game, I had the first level finished. For the first version, we expanded the game to 3 levels. In each level, the sidewalk moves faster, the dog comes at you faster and forces you into a smaller area and stays longer, and the bully gets stronger and bigger. I added small details such as room transitions, music fading away instead of cutting, and boss death animations.  I changed the movement so it was more smooth and accurate, especially the jump mechanics. I did this by adding a z axis, something I didn’t think about doing before. That way the player could jump in different directions and have more control. Next, we added two new powerups. One is a speed limit sign that drops gum when you hit it with your head. The other is cans of soda that you have to kick to gain health. The biggest improvement we made was to the bully fighting. We added sides so that the player could fight from the left or the right side of the bully, and added new skills for both the bully and the player. The player got 2 new skills: Gumdouken and a backpack attack. Gumdouken uses one of the pieces of gum the player picked up to shoot a gum projectile at the bully. If it hits, it sticks to him and damages him. The backpack attack swings the backpack over the players shoulders to hit whatever is in front of him. Also, the player can use a piece of gum to slow the dog behind him for a few seconds, giving him some breathing space. The bully also has new skills. He can throw rocks at the player, jump high into the air and come down hard onto the player, dealing lots of damage, and pound the ground after a period of charging, which deals the most damage out of the skills. Like before, the third bully is the biggest and hardest, using the skills more often and dealing more damage. Finally, we added details such as a new background, a small shadow beneath the player’s feet to help accuracy when avoiding cracks, new block mechanics (if you hold the block for too long it starts shaking and breaks, kind of like the shield in super smash bros), new instruction screens, and last but not least, a new victory screen with fireworks.

<img src="https://jihooncs108.files.wordpress.com/2014/05/1.jpg" width="500">
<img src="https://jihooncs108.files.wordpress.com/2014/05/2.jpg" width="500">
