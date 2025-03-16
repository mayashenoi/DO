**IBM Decision Optimization** represents a family of optimization software that delivers prescriptive analytics capabilities to help you make better decisions and deliver improved business outcomes.\
![VRP versions](https://github.com/mayashenoi/DO/blob/main/Map_of_vrp_subproblems.jpg) \

[**Capcitated Vehicle Routing problem CVRP**](https://github.com/mayashenoi/DO/blob/main/cvrp-cplex(2).ipynb)\
Minimize the number of trips by a vehicle based on the capacity of the vehicle delivering quantities to customers
\
Inspired by [**Victor Terpstra**](https://github.ibm.com/vterpstra) 
\
[**Vehicle Routing Problem with Time Window VRPTW**](https://github.com/mayashenoi/DO/blob/main/vrptw.ipynb)
The VRP concerns the service of a delivery company. How things are delivered from one or more depots which has a given set of home vehicles and operated by a set of drivers who can move on a given road network to a set of customers. It asks for a determination of a set of routes, S, (one route for each vehicle that must start and finish at its own depot) such that all customers' requirements and operational constraints are satisfied and the global transportation cost is minimized. This cost may be monetary, distance or otherwise. The delivery locations have time windows within which the deliveries (or visits) must be made.
The road network can be described using a graph where the arcs are roads and vertices are junctions between them. The arcs may be directed or undirected due to the possible presence of one way streets or different costs in each direction. Each arc has an associated cost which is generally its length or travel time which may be dependent on vehicle type.
Sometimes it is impossible to satisfy all of a customer's demands and in such cases solvers may reduce some customers' demands or leave some customers unserved. To deal with these situations a priority variable for each customer can be introduced or associated penalties for the partial or lack of service for each customer given.\
Inspired by [Narges Movahead](https://github.com/NM001007/CPLEX_VRPTW)

[**Multi Depot Multi capacitated Vehicle Routing Problem with Time Window MCVRPTW**](https://github.com/mayashenoi/DO/blob/main/vrptw.ipynb)
multi-vehicle multi-depot version of CVRP with time windows\
Inspired by [Narges Movahead](https://github.com/NM001007/CPLEX_MVRPTW)
