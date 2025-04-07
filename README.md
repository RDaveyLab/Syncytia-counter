# Syncytia-counter
Cell Profiler pipeliine to count infected cells in the presence of syncytia. 
This pipeline overcomes the issue of counting infected cells when there are syncytia present. It identifies cell nuclei, then measures intensity in the infected channel.
If intensity is above a certain threshold it counts the cell, represented by the nucleus, as infected. 
