# Flutter Installation
  
## System Requirements
  
<img src="https://miro.medium.com/max/700/1*13sEr0fNth295eQGxuuNng.png">
  
## Install the Flutter SDK
  
- **Step 1 :** To download flutter SDK, Go to the official <a href="https://flutter.dev/">website</a> and click on the **Get Started** Button available at the bottom of the page and from there you will be redirected to the following screen.
  
<img src="https://miro.medium.com/max/700/1*kXrkUgvFi_w9b-A4cG5Lhw.png">
  
- **Step 2 :** Now, to download Flutter SDK for your OS, Click on the your OS icon. It will redirected to the page where the SDK zip file will be there which you have to download. Here I am going to download it for Windows.
  
- **Step 3 :** When your download is complete, extract the zip file and place it in the desired installation folder or location, for example, D: /Flutter.
  
**Note: The Flutter SDK should not be placed where the administrator’s permission is required.**
  
- **Step 4 :** To run the Flutter command in regular windows console, you need to update the system path to include the flutter bin directory. The following steps are required to do this:

  - **Step 4.1 :** Go to MyComputer properties -> advanced tab -> environment variables. You will get the following screen
 
<br/>
 
  <img src="https://miro.medium.com/max/700/1*xMoVr7xH9gLd1JG8e-SnSQ.png" height=420 width=320>
     
<br/>
  
- - **Step 4.2 :** Now, select path -> click on edit. The following screen appears.
  
<br/>  
  
  <img src="https://miro.medium.com/max/598/1*0J19c1KtqtPJqfPbRIn0nw.png" height=420 width=320>
  
<br/>
  
- - **Step 4.3 :** In the above window, click on New->write path of Flutter bin folder in variable value -> ok -> ok -> ok.
  
- **Step 5 :** Now, run the $ flutter doctor command. This command checks for all the requirements of Flutter app development and displays a report of the status of your Flutter installation.
  
```
$ flutter doctor
```
  
