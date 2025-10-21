ASCII Art Fade-In Animation (C# Console App)

--Overview--
This program displays an ASCII art logo or banner(whatever you want in text) in the console with a fade in animation effect.  
Each frame gradually reveals more of the artwork while shifting from dark gray to bright white, giving the illusion of light or emergence.
The effect is achieved entirely using standard C# console functions and does not rely on any external libraries.


--Features--
- Smooth fade-in animation using incremental brightness and random reveal.
- Fully configurable number of fade steps and frame delay.
- Works in any standard Windows console.
- Automatically hides the blinking cursor for a clean presentation.
- Can easily be reused with any custom ASCII art or text.


--How It Works--
The program repeatedly redraws the ASCII art several times, each time:
1. Increasing how many characters are shown (based on random chance).
2. Changing the text color from **DarkGray → Gray → White**.
3. Overwriting the previous frame to create a seamless animation.
Once the final fade-in frame is complete, the art is displayed in full brightness, followed by a short message prompting the user to exit.
