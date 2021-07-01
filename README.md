# my tasker config SuperX-dev
 A Repo with the .xml of my Tasker (Automation Android App) Config. Focused on Anti Loss Features and more!
 <br>
 
 
 <h1>Get Tasker!</h1>
 First of all, you nedd to get Tasker (a full automation app) from Google Play store.
 <br>
 It´s 3.49$USD, but it´s totally worth it, for all sorts of Automation!
 <br>
 <b>Get it Now here:</b>
 <br>
 <a href="https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=pt_PT&gl=US">
 <img src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" alt:Tasker height=120>
 </a>
 App made by joaomcgd
 
 <h1>List of Automation on the .xml</h1>
 <h3>Here is a list of all the automation I made available to you on the xml:</h3>
 <h3>AntiLoss SMS Features</h3>
       <i>These are really handy and don´t require an internet connection. Not even to locate your phone (Assuming that your phone has yet battery and it´s not turned off). Just ask a friend to borrow their phone and send an SMS with the Commands ;)</i>
       <br>
       <br>
 <b>Sounds and useful</b>
 <br>
 <ul>
 <li><b>Ring Phone</b>-Command:Ring (Password)
 <li><b>Sound Rob in progress alarm</b>-Command:Stolen (Password)
 <li><b>Stop Souds</b>-Stop all the previous sounds from playing, if they are playing. (You can also stop it, in the notification received on the Phone)-Command:Stop
 <li><b>Make your phone call the SMS sender</b>-Command:Call me Maybe (Password)
  </ul>
  
  <b>Useful Info Grabbers</b>
 <ul>
 <li><b>Get a list of available SMS commands</b>(like this list)-Command:Get Commands
 <li><b>Get your IMEI info</b>-So you can report in case of theft (You´ll need to put the info in the .xml file)-Command:Get IMEI (Password)
 </ul>
 And the most useful feature yet
 <ul>
 <li><b>Get Your Phone Location</b>-Make your phone retrieve the coordinates of it´s current location, and send them to you, even without Internet access. Just <b><i>Make sure that you always leave the Location feature activated</i></b>-Command:Get Locaton (Password)
  </ul>
  
<h4>Music and Media</h4>
This also has music and media features, such activating DND when listening to music or watching a movie.

  
 <h1>What to edit on the backup.xml</h1>
 <b>For these features to work properly, you´ll need first to edit the .xml to work as intended</b>
 <br>
 <h3>How to edit</h3>
 <ol>
 <li>Download the .zip of the code, by clicling on the code button above (or below) and download it as .zip:</li>
 </ol>
 <a href="/SuperX-dev/my-tasker-config-SuperX-dev/archive/refs/heads/main.zip"><img src="https://i.ibb.co/MnCR50p/code-button.png" height=50></a>
 <ol>
 <li>Extract it.</li>
 <li>Open "backup.xml" with notepad (Right click>Open With>Notepad)</li>
 <li>Hit Ctrl+U</li>
 <li>Complete the First field with "(Password) and the second one with password you will use. Just remember to type it the same way when you execute the commands.</li>
 <li>Hit ok</li>
 <li>Do it again with "(Put Your IMEI1)" and "(Put Your IMEI2)" and on the second field insert the IMEI of your phone. Just dial "*#06# on the keypad, as if you would make a call.</li>
 <li>You can also do that with "(Your Phone)" and "(Your Name)", to get this info when the "Get Commands" command is executed.</li>
 </ol>
 
 <h1>How to use it on Tasker</h1>
 Import the .xml to your device and then:
 <ol>
 <li>Open Tasker</li>
 <li>Select The 3 dots</li>
 <li>Go to "Data" > "Restore" > "User Local Backup" and then go to the directory you chose. (Use the upper arrow on the top of the screen to go back in directories.</li>
 </ol>
 
 Or just follow this .gif
 
 <b> And make sure that you allow all the Permission Tasker prompts you to allow during setup.</b>
 
 <br>
 Wait for the .gif
 
<h1>Thank You</h1>
Hope you like it and Happy automation ;)
<hr>
Repo made by SuperX-dev on GitHub
