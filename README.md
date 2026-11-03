# RouteLab – Distance Vector vs Link State

An interactive educational simulator comparing Distance Vector routing and Link State routing.

## Run locally
1. Extract the ZIP file.
2. Open the `RouteLab_Project` folder in VS Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.
4. Select source and destination routers.
5. Run Distance Vector or Link State.
6. Change a link cost and run again to observe the new route.

## Features
- Six-router weighted network topology.
- Editable link costs.
- Distance Vector simulation using iterative Bellman-Ford relaxation.
- Link State shortest-path simulation using Dijkstra's algorithm.
- Routing tables, execution logs, shortest-path cost and hop count.
- Side-by-side conceptual comparison.

## Files
- `index.html` – page structure
- `style.css` – responsive interface
- `script.js` – graph data and routing algorithms
- `Documentation.docx` – project report
- `RouteLab_Presentation.pptx` – presentation slides

## Algorithm notes
The Distance Vector module uses repeated neighbour-based relaxation until no route improves. The Link State module assumes each router has the full topology database and runs Dijkstra from the selected source. Both are simplified educational models, not complete implementations of RIP or OSPF.

## Suggested Excel entry
Project title: RouteLab – Interactive Network Routing Simulator: Distance Vector vs Link State Routing.
Project link: Add the GitHub repository URL after publishing the project.
