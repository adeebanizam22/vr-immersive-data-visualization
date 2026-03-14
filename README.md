# vr-immersive-data-visualization
# Immersive Data Visualization in Virtual Reality

This project demonstrates how datasets can be explored inside a virtual reality environment using Unity.

Instead of traditional dashboards or charts, data is represented as interactive 3D objects inside a virtual space. Users can move around the environment and visually explore the dataset from different perspectives.

This approach is commonly used in **immersive analytics**, simulation environments, and digital twin systems.



## Features

- 3D data visualization using bar structures
- Dataset represented spatially in a VR environment
- Interactive exploration of data inside a virtual space
- Compatible with OpenXR VR systems

---

## Technologies Used

- Unity (3D Engine)
- C#
- OpenXR
- GitHub for version control

---

## How It Works

The system reads a small dataset and converts each value into a 3D bar.

Each bar:
- Height represents the value
- Position represents the index of the dataset

Users can walk around the environment to inspect the data visually.

---

## Example Dataset
{3, 7, 2, 9, 5, 6, 8}


Each number becomes a vertical 3D bar in the virtual environment.

---

## Setup Instructions

1. Install Unity (2022 LTS recommended)
2. Clone this repository
3. Open the project in Unity
4. Enable OpenXR in Project Settings
5. Run the scene

The VR visualization environment will load automatically.

---

## Research Context

Immersive visualization environments allow complex datasets to be explored more intuitively compared to traditional charts or dashboards.

Applications include:

- Digital twin systems
- Simulation environments
- Scientific visualization
- Data analytics in virtual reality

---

## Future Improvements

- Real-time data streaming
- Interactive filtering tools
- Multi-user collaborative VR environments
- Integration with live analytics systems
