# SimMod - Python Simple Climate Model

## Usage
1. Open simmod_controller.py in your editing tool of choice
2. Select desired parameters for RCP, carbon model, climate sensitivity, etc.
3. Run simmod_controller.py in your terminal via python simmod_controller.py
4. Results will be saved as a csv in the SimMod/results folder.

## Notes
The heat diffusion module that converts radiative forcing to global mean
surface temperatures currently breaks for timesteps other than 1 year.
This will be fixed in the near future.

The BEAM carbon model overestimates 2100 atmospheric CO2 concentrations
by ~25% relative to RCP scenarios. Using the pulse response carbon model
is recommended for the time being.# SimMod
