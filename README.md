# 🚗 Driving License E-Exam Desktop Application

A modern, comprehensive, and high-performance desktop application built with Python and Tkinter designed to help candidate drivers prepare for their driving license e-exams. The application simulates the official exam environment with real-time analytics, an interactive optical form, and rigorous exam logic layers.

## 🛠️ Technical Stack & Architecture
* **Language:** Python 3.x
* **GUI Framework:** Tkinter & TTK (Advanced styling and component architecture)
* **Image Processing:** Pillow (PIL) - High-fidelity asset loading and anti-aliased image rendering (`LANCZOS` resampling)
* **Design Pattern:** Object-Oriented Programming (OOP) with fully encapsulated state management

## 🚀 Key Engineering Features

* **Interactive Digital Optical Form:** Built using a dynamic Tkinter Canvas combined with manual MouseWheel bindings (`<MouseWheel>`) and scroll regions, allowing users to jump between 50 questions instantly and track answered/empty questions in real-time.
* **Asynchronous Time Tracking System:** Implements non-blocking background logic using Tkinter's event loop (`.after()`) to handle a strict 45-minute exam countdown without freezing the User Interface.
* **Automated Exam Analytics Engine:** Evaluates user answers instantaneously upon submission. It features custom logic that computes score metrics, checks threshold requirements (>=70 points), and yields visual analytical breakdown (Correct, Incorrect, Empty).
* **Dynamic Post-Exam Review Mode:** Once the exam is finalized, the UI shifts states to block inputs (`tk.DISABLED`) and highlights options retroactively using a smart color schema—green for correct answers and red for incorrect user selections.
* **Modular Multi-Exam Structure:** Decoupled architecture separating the main UI thread from data layers, capable of dynamically importing and mapping distinct question sets (`SINAV_1` to `SINAV_10`).

---

> 🔒 **Project Source Code Status:**
> The core implementation and business logic datasets of this software are kept **Private** due to intellectual property rights, unique visual algorithms, and upcoming commercial distribution plans. If you are a technical recruiter or software manager interested in viewing code snippets or a live operational demo during interviews, please contact me directly!
