# Works in progress


## What is this?

This is an helper tool to rapidly scaffold an AWS CloudFormation template for your service.

The CF template sets up an ECS instance for your Docker container, provides load balancing and autoscaling and connects the dots. You just specify a few details (names, descriptions, environments and ports) in a JSON configuration file and all the basic infrastructure for you app is created automatically.

In the current implementation, you only need to provide a Cluster.
