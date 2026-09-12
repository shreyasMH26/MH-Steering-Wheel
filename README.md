# 🎮 Virtual Steering Wheel — MediaPipe + Python

Control a car game using your hands as a steering wheel — no hardware needed.

Just use your webcam.

## ✨ How It Works

Hold both fists toward the camera like you're gripping a steering wheel.

Tilt your hands left or right to steer.

```text
Both hands level  →  Straight (no key pressed)
Tilt LEFT        →  ← LEFT arrow key
Tilt RIGHT       →  → RIGHT arrow key
Remove hands     →  All keys released instantly


📦 Installation

1. Clone the repository
git clone https://github.com/shreyasMH26/MH-Steering-Wheel.git
cd MH-Steering-Wheel

2. Create a virtual environment
Using a virtual environment keeps the project’s Python packages separate from your system Python.

macOS / Linux
python3.12 -m venv .venv
Activate it:
source .venv/bin/activate

Windows
py -3.12 -m venv .venv
Activate it:
.venv\Scripts\activate

## 3. Upgrade pip
```bash
python -m pip install --upgrade pip

4. Install dependencies
pip install -r requirements.txt

▶️ Run
Start the virtual steering wheel:
python steering_wheel.py


A camera window should open.
Allow camera access if your operating system asks for permission.
Press Q to quit.


🍎 macOS Setup
This project has been tested on macOS.
macOS requires camera permission before Python can access your webcam.
Go to:
System Settings → Privacy & Security → Camera
Enable camera access for the application running Python, such as Terminal, iTerm, VS Code, or your Python launcher.
Then run the script again:
python steering_wheel.py

Keyboard permissions
If the arrow keys are not being detected, macOS may also require Accessibility permission.
Go to:
System Settings → Privacy & Security → Accessibility
Enable access for the application running the Python script.


🎮 Works With Games Using Arrow Keys
The steering wheel can work with games and applications that respond to keyboard arrow keys.
Examples:
* Google Chrome Dinosaur game
* Trackmania
* TORCS
* Hill Climb Racing (browser)
* Browser racing games
* PC games using arrow-key controls
