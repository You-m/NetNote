# DFS（分布式文件系统）服务配置
分布式文件系统（DFS，Distributed File System）使用户更加容易访问和管理物理上跨网络分布的文件。DFS为文件系统提供了单个访问点和一个逻辑树结构，通过DFS，用户在访问文件时不需要知道它们的实际物理位置，即分布在多个服务器上的文件在用户面前就如同在网络的同一个位置。  
通过DFS，可以将同一网络中的不同计算机上的共享文件夹组织起来，形成一个单独的、逻辑的、层次式的共享文件系统。  
DFS是一个树状结构，包含一个根目录和一个或多个DFS链接。要建立DFS共享，必须首先建立DFS根，然后在每一个DFS根下，创建一个或多个DFS链接，每一个链接可以指向网络中的一个共享文件夹。Dfs链接的最大数目是1000。如果Dfs链接的目标文件夹不是Windows 2000文件夹，则该目标文件夹不能有子文件夹。