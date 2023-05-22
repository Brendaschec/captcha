## UPenn Cybersecurity Bootcamp Project 4

### Overview:

**Topic**: Web Development - CAPTCHA Challenge Authentication

**Title**: Robot Until Proven Human: Implementing CAPTCHA

**End Goal**: Implement a server-side, visual and audio based, CAPTCHA system for web applications to deter bot activity.

**List of Technologies to reach the Goal:**
 - Linux VM
 - Docker/Podman
 - NGINX
 - Python
 - MariaDB
 - PHP
 - HTML and CSS
 - JavaScript
 - ImageMagick
 - espeak (espeak-ng)
 - ffmpeg (ffmpeg-free)
 - cURL
 - Web Browser
 - Git
 - Geany/VSCode/Codium/Vim IDE

**The goal will be reached in the following way:**
The Linux VM hosts a Container running the NGINX HTTP server to serve static HTML/CSS/JS content for the frontend of the app. PHP scripts using the cURL library proxy certain requests between the Python backend for handling CAPTCHAs. The backend generates visual and auditory CAPTCHA challenges for GET requests and validates user input for POST requests. ImageMagick and espeak are the libraries and utilities used to generate the challenges. Cookies are used to track a user's CAPTCHA session and the associated answer to the challenge (in RAM). MariaDB stores supplementary data for demonstrating a hypothetical survey web application that uses CAPTCHA verification. The cURL utility and Firefox are used for testing/debugging, while GitHub manages version control.
