# Priston Arduino Macro

Simple automation project using Arduino for keyboard input emulation.

## Features
- Automatic key pressing
- Repetitive action automation
- Custom timing control

## Technologies
- Arduino
- C/C++
- HID Keyboard Emulation

## Objective
Practice hardware automation and embedded programming concepts.

## Pin Configuration

- D9 → Power/active indicator LED
- D8 → Health potion indicator
- D7 → Mana potion indicator
- D6 → Shield skill indicator
- D5 → Attack indicator

The LEDs are used to visually show which action is currently being executed by the macro.

## Current Challenges

Priston Tale received updates where attacks may stop working if the character remains stationary for too long.  
When this happens, the character can also stop healing correctly.

I am still improving the movement system so the character can walk periodically and return to the original position automatically.

## Technologies Used

- Arduino Leonardo
- C/C++
- HID Keyboard Emulation

<img width="876" height="781" alt="Captura de tela 2026-05-26 132144" src="https://github.com/user-attachments/assets/b8f1d66d-904b-4095-8bfa-39730b65197c" />





















