# Post Office Management System

A desktop-based **Post Office Management System** developed in Python using Tkinter. This project demonstrates the practical application of fundamental data structures and algorithms to manage parcel registration, dispatching, status updates, and tracking.

## Features

- **Parcel Registration:** Register parcels with sender and recipient information, destination distance, and an automatically generated six-digit tracking code.
- **Parcel Dispatching:** Select parcels for dispatch based on arrival order (FIFO) or shortest destination distance using a priority queue.
- **Status Management:** Update parcel statuses and maintain a history of changes.
- **Parcel Tracking:** Search for parcels using their tracking codes and view their status history.
- **Graphical User Interface:** Interact with the system through a Tkinter-based desktop interface.

## Data Structures & Algorithms

The project implements several data structures from scratch:

| Data Structure | Purpose |
|---|---|
| Linked List | Store and manage parcel records |
| Queue (FIFO) | Process parcels in arrival order |
| Priority Queue (Min-Heap) | Prioritize parcels by destination distance |
| Stack (LIFO) | Maintain parcel status history |
| Max-Heap | Additional standalone implementation of heap operations |
| Binary Search | Implement parcel lookup by tracking code |

These implementations demonstrate concepts such as dynamic data management, heap operations, searching algorithms, and object-oriented programming.

## Technologies

- **Python** – Core application logic
- **Tkinter** – Desktop graphical user interface
- **Object-Oriented Programming (OOP)** – Modular application design
- **Data Structures & Algorithms** – Custom implementations

## Getting Started

### Prerequisites

- Python 3
- Tkinter (included with many Python installations)

### Installation

1. Clone the repository:

   `git clone https://github.com/setareostvar/Post-Office.git`

2. Navigate to the project directory:

   `cd Post-Office`

3. Run the application:

   `python MainFrame.py`

## How to Use

The application provides four main options:

1. **Receiving Posts:** Enter parcel details to register a new parcel.
2. **Posting:** Choose whether to dispatch the oldest parcel or prioritize the nearest destination.
3. **Set Status:** Enter a tracking code to update the corresponding parcel's status.
4. **Tracking Status:** Retrieve a parcel's status history using its tracking code.

Some dispatch operations require confirmation through the terminal.

## Project Structure

| File | Description |
|---|---|
| `MainFrame.py` | Main application entry point and GUI |
| `Parcel.py` | Parcel records and queue operations |
| `ReceiveParcel.py` | Parcel registration |
| `SendingParcels.py` | Parcel dispatching |
| `SetStatus.py` | Parcel status updates |
| `TrackParcel.py` | Parcel tracking |
| `PriorityQueue.py` | Min-heap-based priority queue |
| `Linked_list.py` | Singly linked list implementation |
| `Stack.py` | Stack implementation |
| `MaxHeap.py` | Standalone max-heap implementation |

## Current Limitations

This project is an educational prototype focused on data structures and algorithms.

- Parcel information is stored in memory and does not persist between sessions.
- Parcel lookup uses binary search, which requires sorted tracking codes; the current queue does not guarantee this ordering.
- Further input validation and error handling would improve reliability.

## Author

**Setare Ostvar**

GitHub: [@setareostvar](https://github.com/setareostvar)
