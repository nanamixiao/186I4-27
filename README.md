# Why Dijkstra's algorithm fails on negative weights



![image](https://github.com/user-attachments/assets/23cce6d4-917f-4f9d-acf5-65ebc49d5082)



Dist[1] = 0 
Dist[2] = 2
Dist[3] = 5 
Dist[4] = 4
Dist[5] = 5



Dist[4] = 3

so ,Dijkstra's algorithm ,the shorest from 1 to 5 is  1-> 2 -> 4 -> 5 but it's not shorest 
The real shorest is 1-> 3 -> 4 -> 5 

So if there are negative edge weights, 
Dijkstra's algorithm will fail because a shorter path may appear later,
but Dijkstra does not go back to recheck. As a result, a path that was originally longer could actually become shorter.

##video 
https://youtu.be/Xe7deTmID54

