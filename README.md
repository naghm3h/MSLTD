## Simpler is better: Multilevel Abstraction with Graph Convolutional Recurrent Neural Network Cells for Traffic Prediction

### Montreal Street Level Traffic Data (MSLTD)

We present the Montreal street-level traffic dataset (MSLTD), which provides  traffic speed over 15-minute intervals. The data was collected from street segments in Montreal, QC, Canada, during the six months from January 2019 to June 2019. The raw data is the historical travel time records on road segments provided by the City of Montreal.

The adjacency matrix corresponding to the road network is calculated based on the road segment information. The variable features are mapped to the nodes, and the static states are considered as the edges to have a fixed graph structure. Each road segment is represented as a node and contains information including its origin and destination detector IDs. If two roads share the same start or end points, then a connection is formed in the graph.

### Multilevel Sequence-to-Sequence (MLS2S) Architecture for a 2-level encoder

![alt text](https://github.com/naghm3h/MSLTD/blob/main/mls2s.png?raw=true)

The output from the last layer of each encoder is used to initialize the decoder. The number of encoder levels equals number of decoder layers.

### Dataset Coverage

<p align="middle">
  <img src="/dataset_coverage.png" width="45%" />
  <img src="/metrla_coverage_gmap.png" width="48%" /> 
</p>

Montreal Street-level Traffic Dataset covering certain strategic road segments of Montreal.

METR-LA dataset sensor distribution.


