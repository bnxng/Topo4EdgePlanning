# Topology data

## File structure
- `TOPO_NAME`:
    - `TOPO_NAME.jpg` : network graph
    - `comp.txt`      : computation capacity, planning budget
    - `graph.txt`     : network graph data (edge-list format: [i, j, bandwidth])
    - `netw.txt`      : ingress nodes, network capacity, traffic types / rates, tolerable latency

## Topology information

| Topology | \#Node | \#Edge | \#Ingress | Degree (Min, Max, Avg) |
| :------: | :----: | :----: | :-------: | :--------------------: |
| `10N20E`          | 10  | 20  | 2 | (3.0, 5.0, 4.0) |
| `20N30E`          | 20  | 30  | 3 | (1.0, 5.0, 3.0) |
| `40N60E`          | 40  | 60  | 3 | (1.0, 7.0, 3.0) |
| `50N50E`          | 50  | 50  | 3 | (1.0, 4.0, 2.0) |
| `60N90E`          | 60  | 90  | 3 | (1.0, 6.0, 3.0) |
| `80N120E`         | 80  | 120 | 3 | (1.0, 6.0, 3.0) |
| `100N150E`        | 100 | 150 | 3 | (1.0, 7.0, 3.0) |
| `Città Studi`     | 30  | 35  | 6 | (1.0, 6.0, 2.3) |

**Notice**:
Topology `Città Studi` is generated based on the data from [**OpenCellID**](https://www.opencellid.org/), which is an open database of cell towers. We considered the Città Studi area around Politecnico di Milano. The other topologies are generated based on Erdös-Rényi [1] random graph by specifying the numbers of nodes and edges.

## References
> [1] P. Erdős and A. Rényi, “On Random Graphs I,” Publicationes Mathematicae Debrecen, vol. 6, pp. 290–297, 1959.
