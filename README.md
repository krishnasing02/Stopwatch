# Stopwatch
A simple, accurate stopwatch built with HTML, CSS, and JavaScript that supports start, stop, lap, and reset controls. It updates the display in real time (hours : minutes : seconds : milliseconds), records lap times, and uses requestAnimationFrame/performance.now() for smooth, reliable timing without drift — all in a lightweight, front-end-only implementation perfect for learning DOM updates and time handling in JavaScript.

# Features
Start / Stop toggle
Reset to zero
Record laps (saved in a visible list)
High-resolution display: HH : MM : SS . ms
Smooth, drift-minimizing timing using performance.now()
Minimal, responsive UI using only HTML and CSS

# How to use
Click Start to begin timing.
Click Lap while running to capture the current time; laps are shown in a list.
Click Stop to pause. Click Start again to resume.
Click Reset to clear the timer and lap list.

# Tech stack
HTML — semantic layout for controls, display, and lap list
CSS — responsive styling and simple animations
JavaScript — timing logic, DOM updates, lap management (no libraries)
