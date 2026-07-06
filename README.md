# Virtual Memory Visualization

## Overview

Virtual Memory Visualization is a simple web-based educational project developed to demonstrate the working of virtual memory paging and page replacement algorithms. It provides an interactive interface where users can enter a page reference string, choose the number of memory frames, and observe how pages are loaded and replaced in memory.

This project was developed as part of a first-year Operating Systems learning activity to understand memory management concepts.

## Features

- Interactive virtual memory simulation
- Supports FIFO (First-In, First-Out) algorithm
- Supports LRU (Least Recently Used) algorithm
- Step-by-step execution
- Auto Play simulation
- Page fault and page hit visualization
- Frame status display
- Activity log for each operation
- Simple and responsive user interface

## Technologies Used

- HTML5
- CSS3
- JavaScript

## Project Structure

```
Virtual-Memory-Visualization/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## How to Run

1. Download or clone the repository.

```
git clone https://github.com/Nadhish-PM/Virtual-Memory-Visualization.git
```

2. Open the project folder.

3. Open `index.html` in any modern web browser.

No additional installation or setup is required.

## How to Use

1. Enter the number of memory frames.
2. Select a page replacement algorithm (FIFO or LRU).
3. Enter the page reference string.
4. Click **Load Sequence**.
5. Use **Step** to execute one page request at a time or **Auto Play** to run the complete simulation.
6. Observe the memory frames and log to understand page hits and page faults.

## Learning Outcomes

- Understand virtual memory concepts
- Learn how paging works
- Compare FIFO and LRU algorithms
- Observe page replacement process visually
- Understand page hits and page faults

## Future Improvements

- Add Optimal Page Replacement algorithm
- Display page fault statistics graphically
- Add TLB simulation
- Improve animations and visualization
- Export simulation results

## Author

**Nadhish PM**

GitHub: https://github.com/Nadhish-PM

Portfolio: https://nadhish.dev

LinkedIn: https://www.linkedin.com/in/nadhish-pm/

## License

This project is developed for educational purposes.
