🚗 Self-Driving Cars Simulation using NEAT and Pygame
Welcome to the Self-Driving Cars Simulation repository! This project demonstrates how to train self-driving cars using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm and visualize the simulation using Pygame.

📜 Table of Contents
Introduction

How It Works

Why NEAT?

Installation

Running the Simulation

Customization

Contributing

License

🌟 Introduction
This project simulates self-driving cars navigating a track using a neural network trained with the NEAT algorithm. The simulation is visualized using Pygame, a popular Python library for creating games and graphical applications.

Key Features:
NEAT Algorithm: Evolves neural networks to control the cars.

Pygame Visualization: Real-time visualization of cars navigating the track.

Customizable Track: Easily modify the track or add new ones.

Interactive Simulation: Watch the cars learn and improve over generations.

🛠️ How It Works
NEAT Algorithm
NEAT (NeuroEvolution of Augmenting Topologies) is a genetic algorithm that evolves neural networks. It starts with simple networks and gradually increases their complexity by adding nodes and connections. The goal is to optimize the network to perform a specific task—in this case, driving a car around a track.

Pygame Visualization
Pygame is used to create a graphical interface where you can watch the cars in action. The cars are controlled by the neural networks, and their performance is evaluated based on how far they can drive without crashing.

Simulation Workflow:
Initialization: A population of cars with random neural networks is created.

Evaluation: Each car drives around the track, and its fitness is calculated based on distance traveled and speed.

Selection: The best-performing cars are selected for reproduction.

Mutation and Crossover: New generations of cars are created by combining and mutating the neural networks of the best performers.

Repeat: The process continues until the cars learn to navigate the track effectively.

🤔 Why NEAT?
NEAT is particularly well-suited for this project because:

No Predefined Architecture: NEAT evolves the structure of the neural network, so you don’t need to design it manually.

Efficient Learning: It starts with simple networks and gradually increases complexity, making it computationally efficient.

Adaptability: NEAT can adapt to different environments and tasks, making it ideal for training self-driving cars.

🛠️ Installation
To run this project, you need to install the following dependencies:

1. Clone the Repository
git clone https://github.com/Diya910/self_driving_cars.git
cd self_driving_cars

2. Set Up a Virtual Environment (Optional but Recommended)
python3 -m venv venv
On linux: source venv/bin/activate  
On Windows: venv\Scripts\activate

3. Install Dependencies
Manual Installation:
pip install neat-python
pip install pygame

🚀 Running the Simulation
Start the Simulation:
Run the following command to start the simulation:
python newcar.py

Watch the Cars Learn:

The simulation will open a Pygame window where you can watch the cars navigate the track.

The cars will improve over generations as the NEAT algorithm evolves their neural networks.

Stop the Simulation:
Close the Pygame window or press Ctrl+C in the terminal to stop the simulation.

🎨 Customization
1. Modify the Track
You can create your own track by editing the map.png file in the repository. Use an image editor to design a new track, ensuring the borders are marked with the color (255, 255, 255, 255) (white).

2. Adjust NEAT Parameters
The NEAT algorithm's behavior can be customized by editing the config.txt file. For example:

Population Size: Increase or decrease the number of cars in each generation.

Mutation Rates: Control how often and how much the neural networks mutate.

3. Change Car Behavior
You can modify the car's speed, sensor range, and other parameters in the Car class within the code.

🤝 Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.

Create a new branch for your feature or bugfix.

Commit your changes.

Submit a pull request.

Please ensure your code follows the project's style and includes appropriate documentation.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🙏 Acknowledgments
NEAT-Python: Official Repository

Pygame: Official Website

Inspiration: This project was inspired by various self-driving car simulations and tutorials.

Enjoy the simulation! If you have any questions or feedback, feel free to open an issue or reach out to me. 🚀