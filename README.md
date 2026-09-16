# Ball-and-Beam-Balancer

A PID system where a ball is balanced on a beam, multiple methods of measurements were used for deciding which method would be the most stablewhich method would prove the most stable
## Results

Achieved sub-2 second settling time and 0% steady-state error on physical hardware.

## Motor Characterization
- Extracted motor parameters through experimental identification
- Compared theoretical and experimental models
- Validated system stability and performance

## Control Architecture
- Cascaded PI controllers (current and velocity loops)
- Lead compensator for position control
- Anti-windup and disturbance rejection

## Key Files
- `motor_identification.m` – Parameter identification
- `controller_design.m` – Controller tuning via root locus and Bode
- `results/` – All experimental and simulation plots
