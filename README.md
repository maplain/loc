
# Introduction

loc visualizes GPU servers in a datacenter. It's composed of the following parts:

- `loc-server`: A server that stores the state of the GPU servers and provides an API to query and update the state.
- `loc-ui`: A web app that visualizes the state of the GPU servers.

## loc-server

loc-server watches the Node objects in the Kubernetes cluster and updates the state of the GPU servers accordingly. It also provides an API to query and update the state of the GPU servers.


## loc-ui

loc-ui is a web app that visualizes the state of the GPU servers. It's built with React and TypeScript. It connects to the loc-server via websocket and receives the updates of the GPU servers' state in real time.
