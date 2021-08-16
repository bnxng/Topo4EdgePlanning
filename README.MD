# Topo4EdgePlanning
Topology data for "EdgePlanning"

## File structure
- `TOPO_NAME`:
    - `TOPO_NAME.jpg` : network graph
    - `comp.txt`      : computation capacity, planning budget
    - `graph.txt`     : network graph data (edge-list format: [i, j, bandwidth])
    - `netw.txt`      : ingress nodes, network capacity, traffic types / rates, tolerable latency

## Topology information

| Topology | \#Node | \#Edge | \#Ingress | Degree (Min, Max, Avg) | Diameter |
| :------: | :----: | :----: | :-------: | :--------------------: | :------: |
| `10N20E`      | 10  | 20  | 2 | (3.0, 5.0, 4.0) | 3  |
| `20N30E`      | 20  | 30  | 3 | (1.0, 5.0, 3.0) | 6  |
| `40N60E`      | 40  | 60  | 3 | (1.0, 7.0, 3.0) | 8  |
| `50N50E`      | 50  | 50  | 3 | (1.0, 4.0, 2.0) | 15 |
| `60N90E`      | 60  | 90  | 3 | (1.0, 6.0, 3.0) | 7  |
| `80N120E`     | 80  | 120 | 3 | (1.0, 6.0, 3.0) | 9  |
| `100N150E`    | 100 | 150 | 3 | (1.0, 7.0, 3.0) | 9  |
| `Città Studi` | 30  | 35  | 6 | (1.0, 6.0, 2.3) | 10 |

**Notice**:
Topology `Città Studi` is generated based on the data from [**OpenCellID**](https://www.opencellid.org/), which is an open database of cell towers. The Città Studi area around Politecnico di Milano is considered. The others are random topologies generated with different numbers of nodes and edges.
