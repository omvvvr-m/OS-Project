# ⚙️ CPU Scheduling Simulator  
### Round Robin vs Shortest Remaining Time First (SRTF)

A web-based simulation tool that compares two popular CPU scheduling algorithms: **Round Robin (RR)** and **Shortest Remaining Time First (SRTF)**.  
Built to help students visualize how processes are executed and how performance metrics differ between algorithms.

---

## 🚀 Features

- 📊 Simulate **Round Robin (RR)** scheduling  
- ⚡ Simulate **SRTF (Preemptive SJF)**  
- 🧠 Visual timeline (Gantt chart style)  
- 📈 Calculates key metrics:
  - Arrival Time (AT)
  - Burst Time (BT)
  - Completion Time (CT)
  - Waiting Time (WT)
  - Turnaround Time (TAT)
  - Response Time (RT)
- 🔄 Adjustable **Time Quantum** for Round Robin  
- 🖥️ Interactive UI (HTML, CSS, JavaScript)

---

## 🧮 Concepts Used

### 🔹 Round Robin (RR)
- Each process gets a fixed time slice (**quantum**)  
- Processes are executed in a circular queue  
- Good for fairness and responsiveness  

### 🔹 Shortest Remaining Time First (SRTF)
- Always selects the process with the **smallest remaining burst time**  
- Preemptive (can interrupt running processes)  
- Minimizes average waiting time  

---

## 📊 Metrics Explanation

| Metric | Description |
|--------|------------|
| AT | Arrival Time — when process enters system |
| BT | Burst Time — execution time required |
| CT | Completion Time — when process finishes |
| TAT | Turnaround Time = CT - AT |
| WT | Waiting Time = TAT - BT |
| RT | Response Time = First Execution Time - AT |

---

## 🖥️ Demo Workflow

1. Enter processes (AT, BT)  
2. Choose algorithm:
   - Round Robin (set quantum)  
   - SRTF  
3. Run simulation  
4. View:
   - Execution order (timeline)  
   - Calculated metrics table  

---

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- Vanilla JavaScript  

---
