# __Top View of Tree__  


Few assumtions --> Left Node of parent is -1 distance away and right node is +1 distance away ( Root == 0).  

* So Idea is take a queue and map.  
* Start from root intert element in queue (root, 0) --> here 0 is position.  
* Now start a loop while queue is not empty and check if node for a particular distance avilable or not in map, if not add and leave.  
* add left node and right node by maintaining +/-1 distance.  
* print full map.  
