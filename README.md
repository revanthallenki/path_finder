# Pathfinding Visualizer

This is a pathfinding visualizer tool built with React.js that allows you to visualize the workings of different pathfinding algorithms on a grid.

## Algorithms Implemented

- **Breadth-First Search (BFS):** Explores all neighbor nodes at the present depth prior to moving on to nodes at the next depth level.
  
- **Depth-First Search (DFS):** Explores as far as possible along each branch before backtracking.

- **A* Search (A-star):** A best-first search algorithm that finds the least-cost path from a given initial node to one goal node (out of one or more possible goals).

- **Dijkstra's Algorithm:** Finds the shortest paths between nodes in a graph, which may represent, for example, road networks.

## Features

- **Grid Setup:** Define start and goal nodes on a customizable grid.
- **Obstacle Placement:** Add walls to simulate blocked areas.
- **Algorithm Selection:** Choose between BFS, DFS, A*, and Dijkstra's algorithms.
- **Visualization:** Watch the algorithms in action with step-by-step visualization.
- **Speed Control:** Adjust the speed of algorithm execution for better understanding.

## Usage

1. **Setup:**
   - Clone the repository: `https://github.com/jajamabhijith/Path_Finder.git`
   - Install dependencies: `cd pathfinding-visualizer && npm install`

2. **Running the App:**
   - Start the development server: `npm run dev`
   - Open localhost to view it in the browser.

3. **Using the Tool:**
   - Select a start point and a goal point on the grid.
   - Add obstacles by clicking or dragging on the grid.
   - Choose an algorithm from the dropdown menu.
   - Adjust the speed slider if desired.
   - Click the "Visualize" button to see the algorithm in action.

4. **Interpreting the Visualization:**
   - Nodes explored are shown in different colors.
   - The final path found is highlighted upon completion.

## Technologies Used

- **React.js:** For building the user interface and managing state.
- **CSS:** For styling and layout.
- **JavaScript (ES6+):** For implementing the algorithms and grid functionality.
- **Bootstrap or Material-UI:** Optional for grid layout and UI components.

## Credits

This project was inspired by the need to visualize and understand various pathfinding algorithms. Credit to the original authors of these algorithms and to the contributors of libraries used.

<!-- ## License

This project is licensed under the MIT License - see the LICENSE file for details. -->




