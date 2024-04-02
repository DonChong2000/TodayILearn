https://www.reddit.com/r/mac/comments/vnp0r5/how_to_open_a_new_chrome_window_with_spotlight/

1.  Launch Script Editor.app
    
2.  Create a new script with the contents shown below.
    
3.  File > Export and choose to save it as an application.
    
4.  Use spotlight to launch your script application whenever you want to open a new chrome window.
    

```
tell application "Google Chrome"
    make new window
    activate
end tell
```