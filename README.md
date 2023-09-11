# CoW2023C3
Challenge Of Wits 2023 Challenge 3
1. Run replacezeropoint.py to convert CSV to usable format. Since pathfinding package determines 0 as wall and 1 as open space and cant determine weightage with decimals, modify the CSV to add 1 and multiply all cells by 10. This does not modify the difference between each cell as eventually weightage will be multiplied by 10 for climbing cost anyways.
2. Run main.py to use pathfinding to determine best route. Check comments at bottom of this file for more debugging info. 
