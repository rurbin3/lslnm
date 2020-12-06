# What is LSLNM Tool?

  - It is A Tool That You Can Use To Download All The Files Saved In A Facebook Automatically.


# Proof:

![Screenshot](proof-1.png)

![Screenshot](proof-2.png)



# Requirements:

  - Google Chrome Browser
  
  - Google Chrome Driver
  
  - Good and Stable Internet Connection
  
  
# How To Set It Up On Linux:

- First, You Need To Install Google Chrome Browser To Your Linux Machine. If You Know How, Do It And Continue and If Not, Follow This Tutorial "https://linuxize.com/post/how-to-install-google-chrome-web-browser-on-ubuntu-18-04/" Then Continue. If You Already Have It, You Can Just Skip.

- After, You Have Installed Google Chrome, Open It As A Normal User(Non-Superuser) Or If You Are as Root, Just Run This Command: google-chrome --no-sandbox.

- After You Have Opened It, Put This In The Browser's Search Bar "chrome://settings/help".

- When You Load The Page, You Should See Google Chrome's Version Number. Keep The Tab Open Since We Are Going To Use The Version Number Or Write It Down For 

  Future Reference.
  
 - Now After You Have Got the Browser's Version Number, You Got To Download Its Respective ChromeDriver. Go To This Link  

  "https://chromedriver.chromium.org/downloads".
 
 - After You Have Opened This Link, You Should See Current Releases. Download The ChromeDriver That Belongs To Your Browser's Version Number.
 
 - After You Have Have Pressed On The ChromeDriver That Corresponds To Your Browser's Version Number, You Will Be Redirected To A Page That Asks What Operating
 
 System Are You Using To Run LSLNM. Just Download Linux ChromeDriver(If You Are On Linux) And Same For Windows OS and Mac OS.
 
 - After You Have The ChromeDriver Downloaded On Your Machine And Google Chrome Browser Installed, We Can Continue.
 
 - Now Download The LSLNM Tool For This Github Repository "https://github.com/PR0PH3CY33/lslnm".
 
 - After You Have Downloaded The Tool, Move The ChromeDriver And Put It In The Same Folder As The LSLNM Tool.
 
 - When You Have Placed ChromeDriver and LSLNM Tool In The Same Folder, Open A Terminal And Navigate To The Folder.
 
 - Make The LSLNM Tool By Executing In The Terminal: chmod +x lslnm
 
 - After Making It Executable, Run This Command As A (Non-Superuser Or It Wont Work) To Start It: ./lslnm
 
 - Now It Asks You For Your Facebook Login And Password (If You Dont Trust Me, Just Create And Use A Dummy FB Account).
 
 - Now After You Have Put Your Facebook Credentials, Put Now The Target Group Link Like This For Example "https://www.facebook.com/groups/1148737265526486/files"
 
 - For Example Target Any Facebook Group, Get Its Link And Add /files At The End Of It Like This: "https://www.facebook.com/groups/OffSec/files". Note: Make SUre 
 
   The Group Has Files Uploaded Or The LSLNM Tool Wont Work And It Will Hang Or Throw An Exception.
   
  - Now Leave It Collects Data Needed For It To Work (It Might Take To 5 Minutes Maximum) And It Will Start Downloading Those Files To Your Machine. They Will Be
  
    Located In The Same Folder You Keep ChromeDriver and LSLNM Tool.
 
 
  
# How To Set It Up On MAC:

  - Same Steps As Linux But Download ChromeDriver For MAC and Different Way To Install Google Chrome Browser (If You Dont Already Have It).
  
  
# How To Set It Up On Windows:

  - If You Are Planning To Run It On Windows, God Have Mercy On You Since You Are A Lost Cause. If You Really Want To Run This On Though, Just Reproduce Those 
  
    Steps Above But Download The ChromeDriver For Windows And Double Click on LSLNM Tool and Everything Should Work Fine.
 
  
# What To Do If You Encounter Any Error?

  - Open A Ticket On Github And I Reply to You ASAP.
 
