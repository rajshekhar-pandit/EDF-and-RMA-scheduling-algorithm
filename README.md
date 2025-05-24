# EDF-and-RMA-scheduling-algorithm
# EDF & RMA Scheduling - Gantt Chart Generator

This is a web-based visualization tool for **Earliest Deadline First (EDF)** and **Rate Monotonic Algorithm (RMA)** scheduling. It allows users to input task parameters and simulate real-time scheduling using animated Gantt charts.

## Features

- Select number of processes (1-10).
- Choose between EDF and RMA scheduling algorithms.
- Input custom parameters for each process:
  - Execution Time
  - Deadline
  - Period
- Adjustable simulation speed using a slider.
- Real-time animated Gantt chart output.
- Responsive and interactive web UI.

## Demo

![Demo Screenshot](demo.png) <!-- Replace this with a real image in your repo if needed -->

## Getting Started

### Prerequisites

A modern browser (Chrome, Firefox, Edge, Safari, etc.)

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/edf-rma-gantt.git
   cd edf-rma-gantt
open index.html
# or double-click index.html in your file explorer


.
├── index.html        # Main HTML file
├── style.css         # Styling for the UI
└── script.js         # Logic for EDF/RMA scheduling and Gantt chart animation
