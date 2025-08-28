# CPU Scheduling Algorithms Visualizer

## Overview

This project is a web-based visualizer for CPU scheduling algorithms. It provides an interactive interface for understanding and analyzing various CPU scheduling methods. The visualizer supports six scheduling algorithms:

1. First Come First Serve (FCFS)
2. Shortest Job First (SJF) - Preemptive
3. Shortest Job First (SJF) - Non-Preemptive
4. Round Robin (RR)
5. Priority Scheduling - Preemptive
6. Priority Scheduling - Non-Preemptive

## External Libraries

The project uses several external libraries and frameworks:

- [Bootstrap 5.0.0](https://getbootstrap.com/) - For responsive design and UI components.
- [jQuery 3.6.0](https://jquery.com/) - For simplifying JavaScript operations.
- [Google Fonts](https://fonts.google.com/) - For custom fonts.
- [Font Awesome](https://fontawesome.com/) - For icons.

## Features

- **Add, Edit, Remove Processes:** Allows you to manage the list of processes including their arrival times, burst times, priorities, and other relevant parameters.
- **Select Algorithms:** Choose one or multiple scheduling algorithms to evaluate the performance.
- **Visualize Scheduling:** Visualize the execution of processes using Gantt charts and other visual aids.
- **Adjustable Time Quantum:** For Round Robin scheduling, you can specify the time quantum.
- **Detailed Output:** Displays ready queue, CPU execution, waiting queue, and other intermediate steps.

## Installation

### Prerequisites

- Web Browser (Google Chrome, Mozilla Firefox, etc.)
- Internet Connection (for loading external resources like Bootstrap and jQuery)

### Steps

1. Clone the repository or download the ZIP file and extract it.
2. Open `index.html` in your preferred web browser.

## Usage

1. **Open the Application:** Open `index.html` in a web browser.
2. **Add Processes:** Click on the "Add Process" button to input process details such as arrival time, burst time, and priority.
3. **Edit/Remove Processes:** Use the "Edit Process" and "Remove Process" buttons to modify or delete existing processes.
4. **Select Algorithms:** Use the dropdown menu to select which algorithms to evaluate.
5. **Set Time Quantum:** If using the Round Robin algorithm, specify the time quantum.
6. **Evaluate:** Click the "Evaluate" button to start the scheduling simulation.
7. **Visualize:** Click the "Visualize" button to see the Gantt chart and other visual outputs.

## Project Structure

- `index.html` - The main HTML file that contains the structure of the application.
- `css/style.css` - The CSS file for styling the application.
- `js/main.js` - The JavaScript file for handling the main functionality of the application.
- `js/algorithm.js` - The JavaScript file containing the logic for different scheduling algorithms.
- `images/image3.png` - The favicon of the application.
