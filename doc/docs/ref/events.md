# Application Events

---
Procedure:
>(**SDL-POLL-EVENT**) → '()

C Function Name:
>`SDL_PollEvent`

Notes:
>Puts a new event into the library.

---
Procedure:
>(**SDL-EVENT-NONE?**) → boolean

Returns:
>`#t` if there are no events otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-TIMESTAMP**) → number

Returns:
>Get the timestamp of an event. All events have a timestamp.

---
Procedure:
>(**SDL-EVENT-QUIT?**) → boolean

Returns:
>`#t` if event is of type `SDL_QUIT` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CLIPBOARD?**) → boolean

Returns:
>`#t` if event is of type `SDL_CLIPBOARDUPDATE` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-TERMINATING?**) → boolean

Returns:
>`#t` if event is of type `SDL_APP_TERMINATING` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-LOW-MEMORY?**) → boolean

Returns:
>`#t` if event is of type `SDL_APP_LOWMEMORY` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-WILL-ENTER-BACKGROUND?**) → boolean

Returns:
>`#t` if event is of type `SDL_APP_WILLENTERBACKGROUND` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-DID-ENTER-BACKGROUND?**) → boolean

Returns:
>`#t` if event is of type `SDL_APP_DIDENTERBACKGROUND` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-WILL-ENTER-FOREGROUND?**) → boolean

Returns:
>`#t` if event is of type `SDL_APP_WILLENTERFOREGROUND` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-DID-ENTER-FOREGROUND?**) → boolean

Returns:
>`#t` if event is of type `SDL_APP_DIDENTERFOREGROUND` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-RENDER-TARGET-RESET?**) → boolean

Returns:
>`#t` if event is of type `SDL_RENDER_TARGETS_RESET` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-RENDER-DEVICE-RESET?**) → boolean

Returns:
>`#t` if event is of type `SDL_RENDER_DEVICE_RESET` otherwise `#f`.



# Windowing Events

---
Procedure:
>(**SDL-EVENT-WINDOW?**) → boolean

Returns:
>`#t` if event is of type `SDL_WINDOWEVENT` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-SYSWM?**) → boolean

Returns:
>`#t` if event is of type `SDL_SYSWMEVENT` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-WIN-SHOWN?**) → boolean

Returns:
>`#t` if window is shown otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_SHOWN`

---
Procedure:
>(**SDL-EVENT-WIN-HIDDEN?**) → boolean

Returns:
> `#t` if window is hidden otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_HIDDEN`

---
Procedure:
>(**SDL-EVENT-WIN-EXPOSED?**) → boolean

Returns:
> `#t` if window is exposed otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_EXPOSED`

---
Procedure:
>(**SDL-EVENT-WIN-MOVED?**) → boolean

Returns:
> `#t` if window is moved otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_MOVED`

---
Procedure:
>(**SDL-EVENT-WIN-RESIZED?**) → boolean

Returns:
> `#t` if window is resized otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_RESIZED`

---
Procedure:
>(**SDL-EVENT-WIN-SIZE-CHANGED?**) → boolean

Returns:
> `#t` if window's size changed otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_SIZE_CHANGED`

---
Procedure:
>(**SDL-EVENT-WIN-MINIMIZED?**) → boolean

Returns:
> `#t` if window is minimized otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_MINIMIZED`

---
Procedure:
>(**SDL-EVENT-WIN-MAXIMIZED?**) → boolean

Returns:
> `#t` if window is maximized otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_MAXIMIZED`

---
Procedure:
>(**SDL-EVENT-WIN-RESTORED?**) → boolean

Returns:
> `#t` if window is restored otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_RESTORED`

---
Procedure:
>(**SDL-EVENT-WIN-ENTER?**) → boolean

Returns:
> `#t` if mouse entered window otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_ENTER`

---
Procedure:
>(**SDL-EVENT-WIN-LEAVE?**) → boolean

Returns:
> `#t` if mouse left window otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_LEAVE`

---
Procedure:
>(**SDL-EVENT-WIN-FOCUS-GAINED?**) → boolean

Returns:
> `#t` if keyboard has gained window's focus otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_FOCUS_GAINED`

---
Procedure:
>(**SDL-EVENT-WIN-FOCUS-LOST?**) → boolean

Returns:
> `#t` if keyboard has lost window's focus otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_FOCUS_LOST`

---
Procedure:
>(**SDL-EVENT-WIN-CLOSE?**) → boolean

Returns:
> `#t` if window is closed otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_CLOSE`

---
Procedure:
>(**SDL-EVENT-WIN-TAKE-FOCUS?**) → boolean

Returns:
> `#t` if window is offered focus otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_TAKE_FOCUS`

---
Procedure:
>(**SDL-EVENT-WIN-HIT-TEST?**) → boolean

Returns:
> `#t` if window has a special hit test otherwise `#f`.

Notes:
>Window Event Type: `SDL_WINDOWEVENT_HIT_TEST`

---
Procedure:
>(**SDL-EVENT-WIN-ID**) → number

Returns:
> The window's id.

---
Procedure:
>(**SDL-EVENT-WIN-X**) → number

Returns:
> The window event's x value.

---
Procedure:
>(**SDL-EVENT-WIN-Y**) → number

Returns:
> The window event's y value.

---
Procedure:
>(**SDL-EVENT-WIN-W**) → number

Returns:
> The window event's width value.

---
Procedure:
>(**SDL-EVENT-WIN-H**) → number

Returns:
> The window event's height value.



# Keyboard Events

---
Procedure:
>(**SDL-EVENT-KEYUP?**) → boolean

Returns:
>`#t` if event is of type `SDL_KEYUP` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-KEYDOWN?**) → boolean

Returns:
>`#t` if event is of type `SDL_KEYDOWN` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-KEYMAP-CHANGED?**) → boolean

Returns:
>`#t` if event is of type `SDL_KEYMAPCHANGED` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-KEY-REPEAT?**) → boolean

Returns:
>`#t` if key press was repeated otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-KEY-UP?** *key*) → boolean

Parameters:
> ***key*** : [A SDL key code.](data.md#scancodes-keycodes)

Returns:
>`#t` if key was released otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-KEY-DOWN?** *key*) → boolean

Parameters:
> ***key*** : [A SDL key code.](data.md#scancodes-keycodes)

Returns:
>`#t` if key was pressed otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOD-UP?** *key*) → boolean

Parameters:
> ***key*** : [A SDL modifier code.](data.md#key-modifers)

Returns:
>`#t` if key was released otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOD-DOWN?** *key*) → boolean

Parameters:
> ***key*** : [A SDL modifier code.](data.md#key-modifers)

Returns:
>`#t` if key was pressed otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CODE-UP?** *key*) → boolean

Parameters:
> ***key*** : [A SDL scancode.](data.md#scancodes-keycodes)

Returns:
>`#t` if key was released otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CODE-DOWN?** *key*) → boolean

Parameters:
> ***key*** : [A SDL scancode.](data.md#scancodes-keycodes)

Returns:
>`#t` if key was pressed otherwise `#f`.



# Text Events

---
Procedure:
>(**SDL-EVENT-TEXT-EDITING?**) → boolean

Returns:
>`#t` if event is of type `SDL_TEXTEDITING` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-TEXT-INPUT?**) → boolean

Returns:
>`#t` if event is of type `SDL_TEXTINPUT` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-TEXT-EDITING-TEXT**) → string

Returns:
>The text being edited.

---
Procedure:
>(**SDL-EVENT-TEXT-INPUT-TEXT**) → string

Returns:
>The text being input.



# Mouse Events

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION?**) → boolean

Returns:
>`#t` if event is of type `SDL_MOUSEMOTION` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOUSE-BUTTON-DOWN?**) → boolean

Returns:
>`#t` if event is of type `SDL_MOUSEBUTTONDOWN` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOUSE-BUTTON-UP?**) → boolean

Returns:
>`#t` if event is of type `SDL_MOUSEBUTTONUP` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOUSE-BUTTON-WHEEL?**) → boolean

Returns:
>`#t` if event is of type `SDL_MOUSEWHEEL` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION-WHICH**) → number

Returns:
>The id of the mouse for the motion event.

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION-X**) → number

Returns:
>The x value of the mouse motion event.

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION-Y**) → number

Returns:
>The y value of the mouse motion event.

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION-X-REL**) → number

Returns:
>The relative x value of the mouse motion event.

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION-Y-REL**) → number

Returns:
>The relative y value of the mouse motion event.

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION-B-LEFT?**) → boolean

Returns:
>`#t` if the left mouse button is down otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION-B-MIDDLE?**) → boolean

Returns:
>`#t` if the middle mouse button is down otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION-B-RIGHT?**) → boolean

Returns:
>`#t` if the right mouse button is down otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION-B-X1?**) → boolean

Returns:
>`#t` if the x1 mouse button is down otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOUSE-MOTION-B-X2?**) → boolean

Returns:
>`#t` if the x2 mouse button is down otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MOUSE-BUTTON-WHICH**) → number

Returns:
>The id of the mouse for the button event.

---
Procedure:
>(**SDL-EVENT-MOUSE-BUTTON-STATE**) → symbol

Returns:
>`'SDL-RELEASED` or `'SDL-PRESSED`.

---
Procedure:
>(**SDL-EVENT-MOUSE-BUTTON-BUTTON**) → symbol

Returns:
>|                   |
 | :---------------- |
 | SDL-BUTTON-LEFT   |
 | SDL-BUTTON-MIDDLE |
 | SDL-BUTTON-RIGHT  |
 | SDL-BUTTON-X1     |
 | SDL-BUTTON-X2     |

---
Procedure:
>(**SDL-EVENT-MOUSE-BUTTON-CLICKS**) → number

Returns:
>The number of time there the mouse button has been clicked.

---
Procedure:
>(**SDL-EVENT-MOUSE-BUTTON-X**) → number

Returns:
>The x value of the mouse.

---
Procedure:
>(**SDL-EVENT-MOUSE-BUTTON-Y**) → number

Returns:
>The y value of the mouse.

---
Procedure:
>(**SDL-EVENT-MOUSE-WHEEL-WHICH**) → number

Returns:
>The id of the mouse for the wheel event.

---
Procedure:
>(**SDL-EVENT-MOUSE-WHEEL-WHICH**) → symbol

Returns:
>`'SDL-MOUSE-WHEEL-NORMAL`, `'SDL-MOUSE-WHEEL-FLIPPED`.

---
Procedure:
>(**SDL-EVENT-WHEEL-BUTTON-X**) → number

Returns:
>The x value of the mouse.

---
Procedure:
>(**SDL-EVENT-WHEEL-BUTTON-Y**) → number

Returns:
>The y value of the mouse.



# Joystick Events

---
Procedure:
>(**SDL-EVENT-JOY-DEV-ADDED?**) → boolean

Returns:
>`#t` if event is of type `SDL_JOYDEVICEADDED` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-JOY-DEV-REMOVED?**) → boolean

Returns:
>`#t` if event is of type `SDL_JOYDEVICEREMOVED` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-JOY-DEVICE**) → number

Returns:
>The id of the joystick device.

---
Procedure:
>(**SDL-EVENT-JOY-BUTTON-UP?**) → boolean

Returns:
>`#t` if event is of type `SDL_JOYBUTTONUP` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-JOY-BUTTON-DOWN?**) → boolean

Returns:
>`#t` if event is of type `SDL_JOYBUTTONDOWN` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-JOY-BUTTON?**) → boolean

Returns:
>`#t` if event is of type `SDL_JOYBUTTONUP` or `SDL_JOYBUTTONDOWN` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-JOY-BUTTON-PRESSED?**) → boolean

Returns:
>`#t` if button was pressed down otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-JOY-BUTTON-DEVICE**) → number

Returns:
>The id of the joystick device.

---
Procedure:
>(**SDL-EVENT-JOY-BUTTON**) → number

Returns:
>The id of the button.

---
Procedure:
>(**SDL-EVENT-JOY-HAT?**) → boolean

Returns:
>`#t` if event is of type `SDL_JOYHATMOTION` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-JOY-HAT**) → number

Returns:
>The id of the hat.

---
Procedure:
>(**SDL-EVENT-JOY-HAT-POS**) → symbol

Returns:
>||
 | :----------------- |
 | SDL-HAT-CENTERED   |
 | SDL-HAT-UP         |
 | SDL-HAT-RIGHT      |
 | SDL-HAT-DOWN       |
 | SDL-HAT-LEFT       |
 | SDL-HAT-RIGHT-UP   |
 | SDL-HAT-RIGHT-DOWN |
 | SDL-HAT-LEFT-UP    |
 | SDL-HAT-LEFT-DOWN  |

---
Procedure:
>(**SDL-EVENT-JOY-HAT-DEVICE**) → number

Returns:
>The id of the joystick device.

---
Procedure:
>(**SDL-EVENT-JOY-BALL?**) → boolean

Returns:
>`#t` if event is of type `SDL_JOYBALLMOTION` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-JOY-BALL**) → number

Returns:
>The id of the ball.

---
Procedure:
>(**SDL-EVENT-JOY-BALL-X-REL**) → number

Returns:
>The motion in the relative x-direction.

---
Procedure:
>(**SDL-EVENT-JOY-BALL-Y-REL**) → number

Returns:
>The motion in the relative y-direction.

---
Procedure:
>(**SDL-EVENT-JOY-BALL-DEVICE**) → number

Returns:
>The id of the joystick device.

---
Procedure:
>(**SDL-EVENT-JOY-AXIS?**) → boolean

Returns:
>`#t` if event is of type `SDL_JOYAXISMOTION` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-JOY-AXIS**) → number

Returns:
>The id of the axis.

---
Procedure:
>(**SDL-EVENT-JOY-AXIS-MOTION**) → number

Returns:
>The current position of the axis.

---
Procedure:
>(**SDL-EVENT-JOY-AXIS-DEVICE**) → number

Returns:
>The id of the joystick device.



# Controller Events

---
Procedure:
>(**SDL-EVENT-CON-DEV-ADDED?**) → boolean

Returns:
>`#t` if event is of type `SDL_CONTROLLERDEVICEADDED` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CON-DEV-REMOVED?**) → boolean

Returns:
>`#t` if event is of type `SDL_CONTROLLERDEVICEREMOVED` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CON-DEV-REMAPPED?**) → boolean

Returns:
>`#t` if event is of type `SDL_CONTROLLERDEVICEREMAPPED` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CON-DEVICE**) → number

Returns:
>The id of the game controller.

---
Procedure:
>(**SDL-EVENT-CON-AXIS?**) → boolean

Returns:
>`#t` if event is of type `SDL_CONTROLLERAXISMOTION` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CON-AXIS-DEVICE**) → number

Returns:
>The id of the game controller.

---
Procedure:
>(**SDL-EVENT-CON-AXIS**) → symbol

Returns:
>||
 | :-------------------------------- |
 | SDL-CONTROLLER-AXIS-LEFT-X        |
 | SDL-CONTROLLER-AXIS-LEFT-Y        |
 | SDL-CONTROLLER-AXIS-RIGHT-X       |
 | SDL-CONTROLLER-AXIS-RIGHT-Y       |
 | SDL-CONTROLLER-AXIS-TRIGGER-LEFT  |
 | SDL-CONTROLLER-AXIS-TRIGGER-RIGHT |

---
Procedure:
>(**SDL-EVENT-CON-MOTION**) → number

Returns:
>The current position of the axis.

---
Procedure:
>(**SDL-EVENT-CON-BUTTON-UP?**) → boolean

Returns:
>`#t` if event is of type `SDL_CONTROLLERBUTTONUP` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CON-BUTTON-DOWN?**) → boolean

Returns:
>`#t` if event is of type `SDL_CONTROLLERBUTTONDOWN` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CON-BUTTON?**) → boolean

Returns:
>`#t` if event is of type `SDL_CONTROLLERBUTTONUP` or `SDL_CONTROLLERBUTTONDOWN` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CON-BUTTON-PRESSED?**) → boolean

Returns:
>`#t` if the button is pressed down otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-CON-BUTTON**) → symbol

Returns:
>||
 | :----------------------------------- |
 | SDL-CONTROLLER-BUTTON-A              |
 | SDL-CONTROLLER-BUTTON-B              |
 | SDL-CONTROLLER-BUTTON-X              |
 | SDL-CONTROLLER-BUTTON-Y              |
 | SDL-CONTROLLER-BUTTON-BACK           |
 | SDL-CONTROLLER-BUTTON-GUIDE          |
 | SDL-CONTROLLER-BUTTON-START          |
 | SDL-CONTROLLER-BUTTON-LEFT-STICK     |
 | SDL-CONTROLLER-BUTTON-RIGHT-STICK    |
 | SDL-CONTROLLER-BUTTON-LEFT-SHOULDER  |
 | SDL-CONTROLLER-BUTTON-RIGHT-SHOULDER |
 | SDL-CONTROLLER-BUTTON-UP             |
 | SDL-CONTROLLER-BUTTON-DOWN           |
 | SDL-CONTROLLER-BUTTON-LEFT           |
 | SDL-CONTROLLER-BUTTON-RIGHT          |

---
Procedure:
>(**SDL-EVENT-CON-BUTTON-DEVICE**) → number

Returns:
>The id of the game controller.



# Audio Events

---
Procedure:
>(**SDL-EVENT-AUDIO-DEVICE-ADDED?**) → boolean

Returns:
>`#t` if event is of type `SDL_AUDIODEVICEADDED` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-AUDIO-DEVICE-REMOVED?**) → boolean

Returns:
>`#t` if event is of type `SDL_AUDIODEVICEREMOVED` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-AUDIO-DEVICE-WHICH**) → number

Returns:
>The id of the audio device.

---
Procedure:
>(**SDL-EVENT-AUDIO-DEVICE-ISCAPTURE?**) → boolean

Returns:
>`#t` if the device is a capture device otherwise `#f`.



# Touch Events

---
Procedure:
>(**SDL-EVENT-FINGER-DOWN?**) → boolean

Returns:
>`#t` if event is of type `SDL_FINGERDOWN` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-FINGER-UP?**) → boolean

Returns:
>`#t` if event is of type `SDL_FINGERUP` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-FINGER-MOTION?**) → boolean

Returns:
>`#t` if event is of type `SDL_FINGERMOTION` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-DOLLAR-GESTURE?**) → boolean

Returns:
>`#t` if event is of type `SDL_DOLLARGESTURE` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-DOLLAR-RECORD?**) → boolean

Returns:
>`#t` if event is of type `SDL_DOLLARRECORD` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-MULTI-GESTURE?**) → boolean

Returns:
>`#t` if event is of type `SDL_MULTIGESTURE` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-TOUCH-ID**) → number

Returns:
>The id of the touch device.

---
Procedure:
>(**SDL-EVENT-TOUCH-X**) → number

Returns:
>The x-axis location of the touch event, normalized (0...1)

---
Procedure:
>(**SDL-EVENT-TOUCH-Y**) → number

Returns:
>The y-axis location of the touch event, normalized (0...1)

---
Procedure:
>(**SDL-EVENT-TOUCH-DX**) → number

Returns:
>The distance moved in the x-axis, normalized (0...1)

---
Procedure:
>(**SDL-EVENT-TOUCH-DY**) → number

Returns:
>The distance moved in the y-axis, normalized (0...1)

---
Procedure:
>(**SDL-EVENT-TOUCH-PRESSURE**) → number

Returns:
>The quantity of pressure applied, normalized (0...1)

---
Procedure:
>(**SDL-EVENT-FINGER-ID**) → number

Returns:
>The id of the finger.

---
Procedure:
>(**SDL-EVENT-GESTURE-ID**) → number

Returns:
>The id of the gesture.

---
Procedure:
>(**SDL-EVENT-GESTURE-NUM-FINGERS**) → number

Returns:
>The number of fingers used to draw the stroke.

---
Procedure:
>(**SDL-EVENT-GESTURE-ERROR**) → number

Returns:
>The difference between the gesture template and the actual performed gesture.

---
Procedure:
>(**SDL-EVENT-MULTI-GESTURE-DTHETA**) → number

Returns:
>The amount that the fingers rotated during this motion.

---
Procedure:
>(**SDL-EVENT-MULTI-GESTURE-DDIST**) → number

Returns:
>The amount that the fingers pinched during this motion.



# Drag & Drop Events

---
Procedure:
>(**SDL-EVENT-DROP-FILE?**) → boolean

Returns:
>`#t` if event is of type `SDL_DROPFILE` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-DROP-TEXT?**) → boolean

Returns:
>`#t` if event is of type `SDL_DROPTEXT` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-DROP-BEGIN?**) → boolean

Returns:
>`#t` if event is of type `SDL_DROPBEGIN` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-DROP-COMPLETE?**) → boolean

Returns:
>`#t` if event is of type `SDL_DROPCOMPLETE` otherwise `#f`.

---
Procedure:
>(**SDL-EVENT-DROP-FILE**) → string

Returns:
>The file name.
