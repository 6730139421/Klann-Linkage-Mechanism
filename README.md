# Four-Leg Klann Mechanism

Term project for 2103322 MECHANICS OF MACHINERY

## Members
- Natheephat 	Wangthongsookshiri	ID 6730136521 	— Symbolic analysis
- Napat 	Ngansungnoen 		ID 6730139421 	— Multibody simulation

## Project Structure
```text
.
├── CAD/                 # STEP files used by the multibody model
├── Symbolicmath/        # MATLAB symbolic analysis files
├── KlanMechanism.slx    # Four-leg Simscape Multibody model
├── start_model.m        # Multibody model startup script
├── Mechanism.avi        # Simulation video
└── README.md
```
## Requirements

### Symbolic Analysis
- MATLAB
- Symbolic Math Toolbox

## Symbolic Mathematical Analysis

The files in `Symbolicmath` describe the planar linkage using geometric constraints and vector-loop equations.

The analysis includes:
- Link positions and orientations.
- Foot trajectories over one complete crank revolution.
- Foot velocity and acceleration.
- An idealized foot-force estimate based on input power.

The symbolic model uses a constant crank speed of 10 rpm.

### How to Run
1. Download and extract the complete repository.
2. Open MATLAB and navigate to the `Symbolicmath` folder.
3. Open and run the analysis script for the desired result.

### Multibody Simulation
- MATLAB
- Simulink
- Simscape
- Simscape Multibody
## Simscape Multibody Simulation

### How to Run
1. Download and extract the complete repository.
2. Keep the `CAD` folder alongside `KlanMechanism.slx`.
3. Open MATLAB in the project root folder.
4. Run:
   ```matlab
   start_model
   ```
5. Click **Run** in Simulink.

## Notes
- All STEP files in the CAD folder are required.
- Crank speed is 10 rpm.
- The frame is fixed; the simulation demonstrates leg motion.

https://github.com/user-attachments/assets/33e0fefd-3a82-4b05-beef-75f063241725





