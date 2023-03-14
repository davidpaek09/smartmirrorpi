#MMM-Spotify

Here are the steps to add a new Spotify user for control on the mirror:

1. Go to this website:   
https://developer.spotify.com/dashboard/  

2. Enter the following information in the sign in:  
email: xnguyen00@g.ula.edu  
password: helloteam8  

3. Go to the Smart mirror-Raspi application and click on Users & Access right next to the Logout button. Enter in your credentials and add a new user.  

4. Activate voice control and say "Hey there, can I add a new user". You can say a variation of this statement, but make sure to start with "Hey there".
   eg: "Hey there, add a new user", "Hey there, I want to add a new user", "Hey there, add a user", etc
   
5. Enter in your name into the website and save. Once you are done, hold up an okay sign and this will take you to the main mirror.  

6. Now, enter into the raspi terminal and enter this command

cd /home/raspi/Team8/magicmirror/modules/MMM-Spotify
node first_auth.js

7. This will load a website url that you should access through the raspi's Chromium browser. Follow the authentication instructions on the page  

8. Run the mirror using the command  

npm start run
