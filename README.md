# One Eye Open

One Eye Open is a macOS utility that prevents the computer from sleeping while a timer is active.

## Features

- Keep the Mac awake forever or for a selected duration.
- Duration options: Forever, 5, 10, 15, 30, 45 minutes, 1, 2, 4, 8, 12, or 24 hours.
- Start, cancel, or reset timers from the menu bar.
- Start, cancel, or reset timers from the Dock menu.
- Optional remaining time display in the menu bar.
- Optional global hotkey to toggle the default timer.
- Configurable default duration for hotkey activation.
- Menu bar only, Dock only, or both.
- Optional start at login.
- Reset Defaults button.

## Finish Actions

When a finite timer ends, One Eye Open stops preventing sleep and can run finish actions.

Available finish actions:

- No sound
- System sound
- Spoken text
- Flash screen

System sound can repeat 1 to 5 times. Spoken text uses the system speech voice. Flash screen shows a full-screen white strobe until user input or timeout.

Finish actions can be adjusted while a timer is running. These active-timer changes do not overwrite the default settings.

Manual timer cancellation does not run finish actions.

## Sleep And Quit Behavior

One Eye Open only prevents sleep while a timer is active.

While a timer is active, the app refuses normal macOS quit, logout, restart, and shutdown termination requests. Cancel the timer first to allow normal termination.

Forced termination, hardware power events, battery depletion, lid close, and administrator policy are not blocked.

## Requirements

- macOS 15 or later
- Apple silicon or Intel Mac

## Install

Download the DMG from the releases page, open it, and drag One Eye Open into Applications.
