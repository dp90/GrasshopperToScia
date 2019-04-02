# GrasshopperToScia

A number of components were made to export a design in Grasshopper to Scia Engineer. As such, a design can quickly be implemented in FEM software to perform calculations and resistance verifications.

The components contain the following functionality:
1. WriteXML combines all model input and creates a file that can be read by Scia Engineer
2. 1D-Elements structures 1D elements into a format that can be used by WriteXML
3. Hinges attaches values to each elements end that signify the nature of the connection: hinged, moment-resistant, etc
4. Supports attaches values to each element end selected that signify the boundary condition type applied
5. PointLoads attaches values to each node selected that represent the point load acting on that node
6. DistributedLoads attaches values to each 1D element selected that represent the distributed load acting on that elemement

The components are also available as .txt files. 

Send me a message, if you are interested in the required .def.xml file to be able to run the models in Scia Engineer.  
