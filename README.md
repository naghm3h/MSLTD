# MSLTD
Montreal Street Level Traffic Data

We present the Montreal street-level traffic dataset (MSLTD), which provides  traffic speed over 15-minute intervals. The data was collected from street segments in Montreal, QC, Canada, during the six months from January 2019 to June 2019. The raw data is the historical travel time records on road segments provided by the City of Montreal.

The adjacency matrix corresponding to the pre-defined graph for GNN methods is calculated based on the road segment information. The variable features are mapped to the nodes, and the static states are considered as the edges to have a fixed graph structure. Each road segment is represented as a node and contains information including its origin and destination detector IDs. If two roads share the same start or end points, then a connection is formed in the graph.
