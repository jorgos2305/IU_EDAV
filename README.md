# IU International University of Applied Sciences

## Course: Explorative Data Analysis and Visualization (DLBDSEDAV01)
Welcome to the repository of the EDAV course.
The task for this project consists in selecting a dataset, showing how it can be visually explored and to gain insights from these visuals as how we should work with it.

### Objectives

The objectives of this project are:
1. To select a dataset of interest
2. To demonstrate and apply the descriptive statistic tecniques learned during the course to describe location, variance, covariance, etc.
3. To create visualizations to highlight interesting aspects of the dataset
4. To describe technical and creative choices (This part is contained only in the written assignment)

## Dataset information

- Name: Elecgtric Vehicle Specs Dataset (2025)
- Source: [Kaggle](https://www.kaggle.com/datasets/urvishahir/electric-vehicle-specifications-dataset-2025/data)
- Features inlcuded:
    - __Brand and Model__: Manufacturer and specific nameplate of the EV.
    - __Car Body Type__: Classification such as hatchback, SUV, sedan, etc.
    - __Segment__: Vehicle segment (e.g., compact, midsize, executive).
    - __Battery Capacity (kWh)__: The gross energy capacity of the battery.
    - __Number of Cells and Battery Type__: Technical battery information, where available.
    - __Efficiency (Wh/km)__: Power consumption rate of the vehicle.
    - __Range (km)__: Estimated driving range on a full charge.
    - __Fast Charging Power (kW)__: Maximum supported DC fast-charging power.
    - __Fast Charge Port Type__: Connector standard (e.g., CCS, CHAdeMO).
    - __Top Speed (km/h)__: Maximum speed of the vehicle.
    - __0–100 km/h Acceleration (s)__: Time to reach 100 km/h from a standstill.
    - __Torque (Nm)__: Maximum torque output, where available.
    - __Towing Capacity (kg)__: Ability to tow loads, provided where applicable.
    - __Cargo Volume (L)__: Luggage space, sometimes approximate or expressed in alternative units.
    - __Seats__: Total seating capacity.
    - __Length, Width, Height (mm)__: Physical footprint of the vehicle.
    - __Drivetrain__: Powertrain configuration (e.g., AWD, RWD, FWD).
    - __Source URL__: Reference link for each car in the [EV database](https://ev-database.org/).

## Environment

This project was developed using a conda environment to ensure consistent dependencies across systems. To reproduce the environment, use `conda env create -f environment.yml`

To activate the environment run `conda activate eda`