_****🚪 Elevator Control System using JK Flip-Flops**_
🧩 Overview**

This project simulates an Elevator Control System that allows users to choose the desired floor through input buttons. The system efficiently handles multiple floor selections, automatically determining the highest floor to visit and sequentially managing elevator movement.

A 7-segment display indicates the current floor number, while JK flip-flops handle the floor traversal logic in reliable manner. An emergency stop switch ensures immediate halting of the elevator during unexpected situations.

**⚙️ Features**

Four Floors: 0, 1, 2, and 3 — each with a dedicated button.

Multiple Floor Handling: If multiple floors are selected, the elevator travels to each in order, stopping at the topmost selected floor.

Real-Time Floor Indication: The 7-segment display shows the current floor.

Emergency Stop: Instantly halts the elevator at any point of travel.

Digital Logic Control: Floor traversal and sequencing are managed using JK flip-flops.

**🧠 Working Principle**

Input Selection:

The user selects one or more floors using buttons 0, 1, 2, or 3.

Each button corresponds to one floor input signal.

Control Logic (JK Flip-Flops):

The JK flip-flops store the elevator’s current state (floor number).

They are triggered based on the selected input and move the elevator up or down to the next target floor.

Sequential Traversal:

The elevator moves floor by floor until it reaches the highest selected floor.

If multiple floors are pressed, the logic ensures the elevator visits each intermediate floor appropriately.

7-Segment Display:

Displays the current floor number dynamically.

Updated every time the JK flip-flop output changes (indicating floor movement).

Emergency Stop:

Overrides all inputs and freezes the elevator’s movement.

Once released, the elevator can resume operation safely.

🔩 Components Used
Component	Description
JK Flip-Flops
7-Segment Display	
Clock 
Logic Gates (AND, OR, NOT)
