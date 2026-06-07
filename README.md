# Statistical Analysis — Navigation and Robotic Execution Studies

MATLAB Live Scripts supporting the statistical analysis reported in:
*Experimental Comparative Validation of Navigation Systems and Autonomous 
Robotic Execution for Percutaneous Nephrolithotomy in Phantom Model.*

## Requirements
MATLAB R2026a or later

## How to Run
1. Update the file path in the **Load** section of `stats_motor.mlx`
2. Run `stats_motor.mlx` —> results are saved to a struct in the workspace
3. Run `report.mlx` to export results to Excel
4. Run `graph.mlx` to generate all figures as PDF

## Scripts
- **stats_motor.mlx** — Core statistical functions. Run this first.
- **report.mlx** — Exports results struct to Excel. Output path configurable at the end of the script. Requires `stats_motor.mlx` to have been run.
- **graph.mlx** — Generates and saves all figures as PDF.
