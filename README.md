# Gleaming-the-Cubes

Gleaming the Cubes

Description

As chief engineer of the Starship Interprize, the task of repairing the hyperstellar, cubic, transwarped-out software has fallen on your shoulders. Simply put, you must compute the volume of the intersection of anywhere from 2 to 1000 cubes.
Input

The input consists of several sets of cubes for which the volume of their intersections must be computed. The first line of each set contains a number (from 2 to 1000) which indicates the number of cubes which follow, one cube per line. Each line which describes a cube contains four integers. The first three integers are the x, y, and z coordinates of the corner of a cube, and the fourth integer is the positive distance which the cube extends in each of the three directions (parallel to the x, y, and z axes) from that corner. 

Following the data for the first set of cubes will be a number which indicates how many cubes are in a second set, followed by the cube descriptions for the second set, again one per line. Following this will be a third set, and so on.A number =0 indicate the end of input.
Output

Your program should process sets all of cubes, outputting the volume of their intersections to the output file, one set per line, until a zero is read for the number of cubes.

Sample Input

2
0 0 0 10
9 1 1 5
3
0 0 0 10
9 1 1 5
8 2 2 3
0

Sample Output

25
9
