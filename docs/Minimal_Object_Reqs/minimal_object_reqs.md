# Minimal Required Data for Object Creation

Upon running the project sibernetic_config_gen 3 files are created, ./configurations/position_muscle.txt, ./configurations/velocity_muscle.txt, ./configurations/connection_muscle.txt .  The contents of those files can be added to a new file with the initial section taken from the demo1 config, the resulting config file will run successfully:

minimal_config_file:
0
100.2
0
66.8
0
668
[position]
<position_muscle.txt contents>
[velocity]
<velocity_muscle.txt contents>
[connection]
<connection_muscle.txt contents>
[end]
