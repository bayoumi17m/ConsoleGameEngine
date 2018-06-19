# Console Based Game Engine

## Background
This project was inspired by a youtube video I saw in which the creator, rather than use openGL or the Unreal Engine, wanted to focus more on the code in the background. This is ideal for experimenting. The Game Engine header wraps up a lot of the initialization and display code.

## Usage
The Game Engine class is abstract, so it must be inherited from. Override the OnUserCreate() function that is needed for the application. (DO IT HERE NOT THE CONSTRUCTOR) Overrise the OnUserUpdate(float fElapsedTime) function with the updates, it gives elapsed time since the last call so things can be dynamic. They should return true until its time to close.

## Additional Information
Input is also handled. Simply look at the m_keys[] array with the virtual
keycode you desire.. bPressed is set for the frame the key is pressed down
in, bHeld is set if the key is held down, bReleased is set for the frame the key
is released in. The same applies to mouse! m_mousePosX and Y can be used to get
the current cursor position, and m_mouse[1..5] returns the mouse buttons.
The draw routines treat characters like pixels. By default they are set to white solid
blocks - but you can draw any unicode character, using any of the colours listed below.

There will be bugs!

## Games Built
- [X] BackTracker Maze
- [X] Asteroids

### Backtracker Maze

### Asteroids
