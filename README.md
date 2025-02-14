# Lineage_Vis
simulated lineage history files

headings:
timestep -> simualtion steps at which the information was captured
cellname ->  each cell has a unique name, this is important for single cell analysis. We can also track lineage by the name "1-1" parental name -> 1-1-1 or 1-1-2 for offspring
cell_Cycle_Time -> cell cycle duration set for the timestep
genome_state -> decribes the on (1) or off (0) state of genes in the system. it is describe as a string. each copy (ploiy) is separated by underscore _
genelist -> usually the names of genes in the system
offspring1_transcriptome -> describes how the transcript counts were randomly distributed to the offspring
offspring2_transcriptome -> describes how the transcript counts were randomly distributed to the offspring
Parent_cell_Cycle_Time -> the current cell cycle time
Offspring1_cell_Cycle_Time -> the inherited cell cycle time (may change depending on the parameters)
Offspring2_cell_Cycle_Time -> -> the inherited cell cycle time (may change depending on the parameters)
cell_Cycle_Phase -> the phase at which the cell was captured: 1 is G1, 2 is S, 3 is G2 and 4 is M
time_elapsed ->  if this number is the same as Parent_cell_Cycle_Time it means the cell divided, however in a an asynchronous system some cells will be in the middle of a cell cycle when the information was captured and this collumn will tell you how far in the cell cycle they are
