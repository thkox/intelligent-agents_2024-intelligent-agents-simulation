# Intelligent Agents (2024) - Intelligent Agents Simulation

## Project Overview

This project simulates two competing teams of intelligent agents tasked with gathering resources from a shared environment, with the goal of collecting specific materials (wood, stone, gold) and returning them to their respective villages. Each team’s agents have unique attributes such as energy consumption, speed, and resource carrying capacity, which influence their behavior and effectiveness in the simulation. The environment is randomly generated, consisting of a grid filled with villages, resources, and obstacles that agents must navigate. Agents use pathfinding algorithms like DFS (Depth-First Search) and A* to explore the map and gather resources. As agents interact with one another, they can exchange knowledge and even reproduce, improving the overall performance of their team. The simulation ends when a team collects all the required resources or loses all its agents due to energy depletion. The project was developed using Godot Engine as part of the "Intelligent Agents" course in the 8th semester at the University of Piraeus.

## Course Information

- **Institution:** University of Piraeus
- **Department:** Department of Informatics
- **Course:** Intelligent Agents (2023-2024)
- **Semester:** 8th

## Features

1. **Agents' Behavior**

    The agents in the simulation have distinct attributes, such as:

    - Energy consumption
    - Speed
    - Resource carrying capacity (wood, stone, and gold)

    Agents can move freely across the grid-like map, avoiding obstacles and interacting with the environment by discovering resources and returning them to their respective villages.

2. **Map and Environment**

    The environment is a randomly generated grid (from 25x25 to 100x100 tiles) containing:

    - **Villages:** The starting point for each team of agents.
    - **Resources:** Tiles containing wood, stone, or gold.
    - **Obstacles:** Impassable tiles that agents must navigate around.

3. **Simulation Goals**

    - Each team of agents is tasked with gathering a specific amount of each resource (determined by the user at the start).
    - The simulation continues until one team collects all the required resources or all agents on a team are eliminated due to energy depletion.

4. **Intelligent Decision-Making**

    The simulation ends when:

    - A team has successfully collected the required resources.
    - One team has lost all its agents due to lack of energy.

## Implementation

The project was implemented using Godot Engine 4.2.2. Godot was chosen due to its lightweight, open-source nature, and its suitability for 2D simulations. Free assets from Kenney.nl were used to create the visual elements of the simulation.

## Documentation and Resources

- Full project details can be found in the [Project-documentation.pdf](./doc/Documentation.pdf)
- A detailed walkthrough video is available: [Project-video.mp4](./video/video_presentation.mp4)

## Screenshots
### Main Menu
<img width="750" src="https://github.com/ApostolisSiampanis/intelligent-agents/blob/main/screenshots/Picture1.png">

### Configuration Settings
<img width="750" src="https://github.com/ApostolisSiampanis/intelligent-agents/blob/main/screenshots/Picture2.png">

### Simulation Screen
<img width="750" src="https://github.com/ApostolisSiampanis/intelligent-agents/blob/main/screenshots/Picture3.png">

### Visited tiles based on an agent's knowledge
<img width="750" src="https://github.com/ApostolisSiampanis/intelligent-agents/blob/main/screenshots/Picture4.png">

### Following an agent's movement
<img width="750" src="https://github.com/ApostolisSiampanis/intelligent-agents/blob/main/screenshots/Picture5.png">

### End of simulation
<img width="750" src="https://github.com/ApostolisSiampanis/intelligent-agents/blob/main/screenshots/Picture6.png">

## Setup Instructions

1. **Install Godot Engine 4.2.2** from [Godot Engine](https://godotengine.org/).
2. Clone the repository:

    ```bash
    git clone https://github.com/ApostolisSiampanis/intelligent-agents.git
    ```

3. Open the project in Godot Engine.
4. Run the simulation by selection the `main.tscn` scene and clicking "Play".

## Contributors
<table>
  <tr>
    <td align="center"><a href="https://github.com/thkox"><img src="https://avatars.githubusercontent.com/u/79880468?v=4" width="100px;" alt="Theodoros Koxanoglou"/><br /><sub><b>Theodoros Koxanoglou</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/ApostolisSiampanis"><img src="https://avatars.githubusercontent.com/u/75365398?v=4" width="100px;" alt="Apostolis Siampanis"/><br /><sub><b>Apostolis Siampanis</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/dimitrisstyl7"><img src="https://avatars.githubusercontent.com/u/75742419?v=4" width="100px;" alt="Dimitris Stylianou"/><br /><sub><b>Dimitris Stylianou</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/anthonyrouss"><img src="https://avatars.githubusercontent.com/u/79643636?v=4" width="100px;" alt="Anthony Roussos"/><br /><sub><b>Anthony Roussos</b></sub></a><br /></td>
  </tr>
</table>

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
