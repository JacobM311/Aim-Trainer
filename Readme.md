Beat Detection

Summary
The Beat Detection module is a powerful, easy-to-integrate solution designed to enhance  games by synchronizing gameplay elements with musical beats and frequencies. It analyzes audio in real-time to detect beats and allows game developers to create responsive, rhythm-based gameplay experiences. Perfect for rhythm games where timing and precision are key.

Features:
- Real-time audio analysis to detect beats or meaningful audio changes.
- Frequency-driven architecture, easy to integrate with game logic.
- Supports multiple frequency bands for nuanced beat detection.
- Lightweight and optimized for performance.

Installation
To install the Beat Detection module in your Unity project, follow these steps:

1. Download the BeatDetection.cs file in the directory.
2. Import the file into your Unity project.
3. Implement your own code to interact with things based on different frequencies within the Beat Detection script.

Example Usage
An example usage that I had in my project was to apply a size scaling to enemy objects in my aim trainer to create a compelling aim training scenario that is both engaging through its utilization of music but also because it creates new aim training scenarios from already created aim training scenarios, and adds in a new type of challenge to aim training scenarios by creating dynamic targets in a scenario. I did this by refrencing the BeatDetection.freqBand[] and applying the value to the scale of the object in the update function of the script attached to my target components.