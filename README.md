# Simple WinForms Counter (Timer Exercise)

A practical C# Windows Forms application that demonstrates the use of the `Timer` control. This project focuses on managing background tasks, updating the UI dynamically, and controlling execution flow through Start, Stop, and Reset functionality.

## Project Features
* **Real-time Counting:** Uses a `Timer` to increment a counter value at specific intervals.
* **Flow Control:** * **Start:** Activates the timer and enables the counter.
    * **Stop:** Pauses the counting process immediately.
    * **Reset:** Sets the counter back to zero and restarts the sequence.
* **Dynamic UI Updates:** Reflects the current counter value instantly on a Label.
* **Interactive Design:** Simple button-based interface with background color customization (Maroon theme).

## Technical Concepts Covered
* **System.Windows.Forms.Timer:** Understanding the `Tick` event and `Interval` property.
* **State Management:** Using a private variable (`Counter`) to track the application state.
* **Event Handling:** Wiring multiple buttons to control a single background component.

## How to Run
1. Open the solution file (`.sln`) in Visual Studio.
2. Build and run the project (`F5`).
3. Click **Start** to begin the counter, **Stop** to pause, or **Reset** to start over.
