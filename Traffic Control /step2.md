
### [Canary Deployments](https://istio.io/latest/blog/2017/0.1-canary/)

 The idea behind canary deployment (or rollouts) is to introduce a new version of a service by first testing it using a small percentage of user traffic, and then if all goes well, increase, possibly gradually in increments, the percentage while simultaneously phasing out the old version. If anything goes wrong along the way, we abort and rollback to the previous version. 