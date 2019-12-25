# GossipPushSum-Simulator
An Elixir based convergence simulator for Gossip and Push sum algorithms for various topologies 


RUNNING THE CODE​: ● Extract the contents of the zip folder in your desired location. ● After extracting, open cmd/terminal to the folder which has the mix.exs file. ● In the cmd/terminal run the command- “​mix escript.build​”. This will build the            executable application. ● Run the command in the following format: For windows: “​escript gosspush <number of nodes> <topology> <algorithm>” For macOS/Terminal: “ ​./gosspush <number of nodes> <topology> <algorithm>” Topologies can be: ​full | line | random2d | torus3d | honeycomb | randhoneycomb Algorithm can be: ​gossip | pushsum Note: ​Please give a perfect cube value for number of nodes in Torus 3D topology. 
 
WHAT IS WORKING:  Convergence is attained for the following algorithms: ● Gossip ● Push-Sum   ​Convergence is attained for the following network topologies: ● Full ● Line ● Random 2D ● 3D Torus ● Honeycomb ● Random Honeycomb
