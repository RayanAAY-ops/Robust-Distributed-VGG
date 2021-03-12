# Robust-Distributed-VGG
This is a simulated environment that conceptualize a network of IOT devices, where every devices contains one part of the pre-trained model represented by a class. I also made the network resilient to electrical disruption and robust to intermediate node fail, by adding an extension layer in the final node that will re-connect the initial node with the final layer 

I distribute a VGG16 network on three classes, where every class simulate a node in a network. 
<img width="1152" alt="Capture d’écran 2021-03-12 à 4 51 23 PM" src="https://user-images.githubusercontent.com/55285736/110964168-333b9880-8353-11eb-8bca-28f1c468ade3.png">

