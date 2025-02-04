# Solar System Simulation

A Python-based solar system simulation using Pygame that visualizes the orbits of Mercury, Venus, Earth, and Mars around the Sun, taking into account gravitational forces and astronomical units.

## Features
- Realistic planetary orbit simulation based on gravitational forces
- Visual representation of planetary movements
- Distance tracking from Sun for each planet
- Orbital path visualization
- Accurate scaling using astronomical units (AU)

## Requirements
- Python 3.x
- Pygame

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/solar-system-simulation.git
cd solar-system-simulation
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage
Run the simulation:
```bash
python planetary_simulation.py
```

## Controls
- Close the window to exit the simulation

## Technical Details
- Uses real astronomical values for:
  - Planet masses
  - Orbital velocities
  - Distances (in AU)
  - Gravitational constants
- Implements Newton's law of universal gravitation
- Time scale: 1 day per timestep
- Distance scale: 1 AU = 250 pixels

## File Structure
```
solar-system-simulation/
├── planetary_simulation.py
├── requirements.txt
└── README.md
```

## License
MIT License

## Contributing
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## Credits
Created by [Your Name]
