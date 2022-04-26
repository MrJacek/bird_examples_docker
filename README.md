# bird_examples_docker
## Overview
This repo contains a very minimal playground to experiment with BGP using BIRD. This is meant to accompany the article at http://packetfire.org/post/intro-to-bgp/ however there is nothing stopping you from using this as a toy environment to play with routing.

Alternatively a similar environment is provided that leverages full virtualization using vagrant as the provisioner. This repo can be found at https://github.com/ncatelli/bird_examples.
## Moje modyfikacje
* Dodałem 4 bird-a jako w raz 3 siecia
* Doałem 2 clientów żeby można było im swopodnie ip -ki dodawać ( trzeb tylko default gateway na nich ustawić na 10.0.0.10 czyli peer1)


