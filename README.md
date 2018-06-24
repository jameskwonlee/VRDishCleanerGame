Kitchen Project - Updated
by James Kwon Lee
6.24.18 

KitchenProject.uproject

Unreal Version: 4.15.3

Headset: Oculus Rift

3rd Party Assets: 
All of the following are downloaded from gamemasteraudio.com--
collect_item_02.wav - Used for when plate is succesfully cleaned and point is gained
happy_collect_item_07.wav - Used when game time has elapsed fully (i.e. game clock hits 0).
points_ticker_bonus_score_reward_single.wav - Used when "Push Me!" Button is pressed

Design of User Experience and Timer:
On awake, a user is able to see a red button that is labeled with a text, "Push Me!". Upon pushing the button, the "Push Me!" text disappears, 
and the visible timer counts down (from 35 seconds). 

Plates are spawned in three different waves. Immediately, a random integer value wave of 7 to 11 Plates spawn from the cabinet behind the user.
The user can pick up the plates and drop them in the sink, where it will take 2-seconds 
to "wash". Once the plate is "washed", the plate disappears from the play area, and a point is rewarded as a sound cue is played. 
After about 9 seconds, a Second Wave of plates are spawned in the cabinet area. 
Then after 14 seconds, a Third Wave of plates are spawned. 

Accumulated points are visible on a curved text via a 3D widget in front of user (the user can also see the countdown game clock in this area). 

Once the game clock hits 0 seconds, all the plates from the gameplay area disappear via an event dispatcher, and an end game sound cue is played. 
The "Push Me!" text reappears above the button after gameplay is ended. 
The user can push the button again to restart the game. Once the button is pushed, the game countdown clock resets to 35 seconds, and the score is reset to 0. 

User's Controls and Experience:
Two Magic Wands are used as the left and right "hands". 
Squeezing the Oculus Touch grip buttons will allow user to pick up plates. Releasing the Grip buttons will drop the plates.
The pick up and drop off (sphere) areas are at the tip-ends of each wand. 
*The grip controls on the wands have been updated so that one controller's "grip" squeeze does not interfere with the pick up or drop off "grip" of the other controller. 

Either or both wands can "touch" the "Push Me!" button to start the game. 

