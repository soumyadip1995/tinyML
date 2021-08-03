## TinyML from scratch

#### Keeping in mind (Before I forget)

- Optimization
- Scalable
- Low power.

### Goals

- Find out what we need to work on.
- Learn the full stack from architecture to deployment.(Can we learn about the different layers of abstraction).

 Using the layers of abstraction to suit our purpose. Better Optimize.
- building a model. Pytorch support Maybe. DL model on MCU.
- Better optimized models. Memory optimization.

- Read the paper on MCUnet:- [https://hanlab.mit.edu/projects/tinyml/mcunet/](hanlabmit). Study the full stack from scratch.


This will be useful towards the last layers of the stack.
- While using a compatible MCU with STM32 , keep in mind SRAM usage and latency. [https://github.com/mit-han-lab/tinyml/tree/master/mcunet](mit-han-lab). 

### Neural Architecture Search

Network ARch.


- Search space. [https://lilianweng.github.io/lil-log/2020/08/06/neural-architecture-search.html](lilianwengblog). How can we reduce overall complexity in the algos. Can we reduce complexity by coming up with better policy optimizations within the network.


## Open questions.

- Working with a larger dataset. What are the prereqs in terms of the hardware we use

- Can we do feature learning (Better models) (Higher or lower feature learning whichever one is feasible). Maybe autoencoders will work. (Task aware autoencoders). Look into autoencoders. 
- Aim for maximum returns. Better Policy optimization. Can we aim for better methods.

- FLoating point operations. FP optimization. Achieving Higher FLOPs inspite of the memory constraints.

### TO DO:


- Read the paper on MCUnet:- [https://hanlab.mit.edu/projects/tinyml/mcunet/](hanlabmit). Study the full stack from scratch.
- Learn more about Memory optimization.
- Read about using datasets on Low power devices