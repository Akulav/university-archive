# Clock Test (Pilot)

A WinForms visual-memory test. The app asks a question, briefly shows six randomly chosen clock images, then hides them. You answer from memory.

## How it works

1. Click **Start**. A question appears for a few seconds.
2. Six random images from the `Images` folder are drawn on the canvas.
3. After a timeout (6 seconds by default) the images disappear.
4. Type your answer, which is checked against the generated answer.

## Running

1. Open `ClockTest.sln` in Visual Studio and build.
2. Put an `Images` folder with `.png` clock images next to the built executable. The images are not included in this repository.
3. Run the app.
