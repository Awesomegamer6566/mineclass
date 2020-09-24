# MineClass

MineClass is a re-implementation of Minecraft Education Edition's Classroom Mode companion app. While Classroom Mode is very useful for classroom usage, it often lags 
to the point of being completely unusable. MineClass also adds class lists/rosters so that you can save the students in a class, and more easily see who is missing -
this is super-useful for remote learning. 

## Installation
Native apps coming soon!

For now, you'll need to install python 3.7+, and pyqt5 and pyqtgraph; or just `pip install -r requirements.txt`

## Usage
- Start MineClass
- Start Minecraft Education Edition and log in
- Go to Settings -> Profile
- Disable "Require Encrypted Websockets" (flick the switch to the left)
- Exit settings, and open a Minecraft World
- Copy the connect string from MineClass (press the copy button)
- In Minecraft, open a Terminal (press T) then paste the connect string (something like `/connect 192.168.3.12:65456`)
- View and control your world from within MineClass!