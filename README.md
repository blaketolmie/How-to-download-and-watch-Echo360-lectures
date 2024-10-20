# Echo360 Downloader and Viewer

## Downloading Lectures from Echo360

To download lectures from Echo360:

1. Clone the Echo360 downloader tool using:  
   ```bash  
   git clone https://github.com/ronandalton/echo360-downloader.git 
2. Export course cookies, [Export All Cookies](https://chromewebstore.google.com/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc) using the "Get Cookies.txt" Chrome extension. Place the cookies.txt file in the `echo360-downloader` folder.  
3. Run the main.py file and provide the Echo360 course link when prompted. The script will automatically download all lectures from the course using the cookies.txt file downloaded from (2).  
Lectures will be neatly organized into separate folders, e.g., Lecture 1, Lecture 2, etc.  
  
> To download multiple courses at once, use the terminal:  
>    ```bash  
>    python main.py -o "C:\Users\Bob\Echo360\ENME203" -c "ENME203.txt"  
  
> To download multiple courses concurrently, open a new terminal for each course then run the terminal prompt (make sure to update the cookies.txt file to course-specific and output directory accordingly).

## Watching Downloaded Videos
For Echo360 type dual-source lectures (such as slides and video streams), download [gridplayer](https://github.com/vzhd1701/gridplayer) to play both sources of the lecture synchronously.  
+ To play synchronously  
![Play Synchronously](images/play_synchronously.png)

+ To view only one source while maintaining sync, double-click on the video you want to make full screen. Double-click again to return to dual view.  
![Echo360 View](images/echo360_like_view.png)

+ To replicate the view of Echo360, change the aspect ratio to "None".  
![Change the Aspect Ratio to "None"](images/change_the_aspect_ratio_to_None.png)  

+ Keyboard Shortcuts  
![Speed](images/keyboard_shortcuts_speed.png)  
![Jump (to)](images/keyboard_shortcuts_jump_to.png)   


