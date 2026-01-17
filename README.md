Markdown
# Personal Portfolio / Profile Page

A sleek, responsive personal landing page featuring a glassmorphism design, real-time GitHub repository fetching, and an integrated audio player. This project is designed to be a "drop-in" profile page that automatically pulls your latest work.

## ✨ Features

-   **Dynamic GitHub Integration**: Automatically fetches your profile picture, bio, social links, and latest 12 repositories using the GitHub API.
-   **Glassmorphism UI**: Modern aesthetic with blurred backgrounds, glowing orbs, and scanline effects.
-   **Integrated Music Player**: Custom-built audio player with play/pause, mute, progress bar, and visualizer animation.
-   **Fully Responsive**: Optimized layout for both desktop (no scroll) and mobile (natural scroll) experiences.
-   **Visual Effects**: CRT scanlines, floating background orbs, and glitch text effects on load.

## 🚀 Setup & Configuration

### 1. File Structure
Ensure your folder looks like this:
```text
/project-folder
  ├── index.html       (The main file)
  ├── video.mp4        (Background video loop)
  └── music.mp3        (Background music track)
```
### 2. Configure Username
Open index.html in any text editor (Notepad, VS Code, etc.) and look for the script section at the bottom. Change the username variable to your GitHub username:


```// Change "jxdexiao" to your actual GitHub username
const username = "jxdexiao";
```
### 3. Add Media Files
Background Video: Place a video file named video.mp4 in the same directory.

Music: Place an audio file named music.mp3 in the same directory.

Note: Modern browsers (Chrome/Safari) block audio from playing automatically. The user must interact with the page (click play) to start the music.

🎨 Customization
Changing Colors
You can change the primary accent color (currently Gold) by modifying the CSS variable at the top of the <style> section:

```
:root {
    /* Change this hex code to your preferred color */
    --primary: #D4AF37; 
    /* ... other variables */
}
```
Social Links
The code automatically detects if you have a Blog or Twitter linked in your GitHub profile settings. If these are set on GitHub, the icons will appear automatically.

📦 Dependencies
Font Awesome: Used for icons (CDN link included).

Google Fonts: Uses 'Outfit' and 'Space Mono'.

GitHub API: No API key required for public data.

📄 License
Feel free to use and modify this code for your personal use.
