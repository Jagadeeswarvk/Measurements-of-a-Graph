# Measurements-of-a-Graph

The C++ project to find the graph measurements like - Length, Eccentricity, Radius, Diameter, Centre of Graph

1. Length – Length of the graph is defined as the number of edges contained in the graph.

![260432001-bf5a431d-a1be-4d5b-bb43-bfa93e93bfb0](https://github.com/Jagadeeswarvk/Measurements-of-a-Graph/assets/108130988/11e8c4c0-5f80-4e1d-a44a-f17cb2402b49)

2. Eccentricity of graph – It is defined as the maximum distance of one vertex from other vertex. The maximum distance between a vertex to all other vertices is considered as the eccentricity of the vertex. It is denoted by e(V).

![260432313-accde8a8-7152-4d0b-95aa-9397a6231ae7](https://github.com/Jagadeeswarvk/Measurements-of-a-Graph/assets/108130988/b8499270-ddf1-49ca-a1ce-54e11638ded3)

     Eccentricity from:
    (A, A) = 0
    (A, B) = 1
    (A, C) = 2
    (A, D) = 1
        Maximum value  is 2, So Eccentricity is 2

3. Radius of graph – A radius of the graph exists only if it has the diameter. The minimum among all the maximum distances between a vertex to all other vertices is considered as the radius of the Graph G. It is denoted as r(G). It can also be found by finding the minimum value of eccentricity from all the vertices.

![260432785-565db8be-786f-449a-81b1-9b2d8c5a8027](https://github.com/Jagadeeswarvk/Measurements-of-a-Graph/assets/108130988/0643539c-c4a2-404b-babc-6b7c638efee5)

    Radius: 2
     All available minimum radius: 
     BC → CF,
     BC → CE,
     BC → CD,
     BC → CA
     
4. Diameter of graph – The diameter of graph is the maximum distance between the pair of vertices. It can also be defined as the maximal distance between the pair of vertices. Way to solve it is to find all the paths and then find the maximum of all. It can also be found by finding the maximum value of eccentricity from all the vertices.

![260433115-8de65831-84a0-48e4-8a4a-e801f9868eca](https://github.com/Jagadeeswarvk/Measurements-of-a-Graph/assets/108130988/d4785f11-9388-4142-82a5-6873465a60af)

    Diameter: 3
    BC → CF → FG  
    Here the eccentricity of the vertex B is 3 since (B,G) = 3. (Maximum Eccentricity of Graph)

5. Centre of graph – It consists of all the vertices whose eccentricity is minimum. Here the eccentricity is equal to the radius. For example, if the school is at the center of town it will reduce the distance buses has to travel. If eccentricity of two vertex is same and minimum among all other both of them can be the center of the graph.
   
  ![260433398-0ce6cae1-c557-4c3b-b48e-95d32242fccb](https://github.com/Jagadeeswarvk/Measurements-of-a-Graph/assets/108130988/6d761657-6966-4050-b4f3-c2eec95692e1)

    Centre: A  
    Inorder to find the center of the graph, we need to find the eccentricity of each vertex and
    find the minimum among all of them. The minimum eccentricity vertex will be considered as the center.

