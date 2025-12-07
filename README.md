# PhotonMesh
A Distributed GPU Image Processing Cluster

You send an image to a central server.  
The server **splits the image into tiles** and sends each tile to different **GPU worker nodes** over the network.  
Each worker processes its tile using **CUDA kernels** and returns the result.  
The server stitches the final image back together.

This creates a tiny "GPU compute cluster" you can run on multiple laptops or desktops.
