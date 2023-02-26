## Crystal
Businesses have always used always used data and analytics to make business decisions.

As a result of exponential data growth and the challenges associated with processing large amount of data, a number of fast, in-memory analytical solutions have been developed in recent years, including systems Hyper and Vectorwise. Several vendors now offer a high-performance in-memory analytics system. As data volumes continue to increase and Moore’s Law no longer offers the hope of better CPU performance, researchers have increasingly looked at new architectures to increase performance. Of particular interest are massively parallel GPU-like architectures.

Data analytics are inherently highly parallel and thus are a perfect fit for the execution model of GPUs. Over the past decade, GPU hardware has improved significantly. A modern GPU has 16GB-24GB of high-bandwidth memory capable of delivering 480-750GBps memory bandwidth and 14 Tflops of compute. This can be compared to a single CPU that has 1TB of memory with 60GBps memory bandwidth and ~ 1TFlop of compute. As most data analytic operations are memory- or compute- bound, significant performance gains are plausible from running on GPUs. It is also possible to have multiple GPUs attached to a single host (up to 8 today), which will further enhance performance.

However, there are a number of challenges associated with using GPUs for data analytics. In this project, we are building a hybrid GPU-CPU data processing system called Crystal, focusing on new GPU-data processing algorithms as well as a cost model for predicting on which processor to run computation.

### Participants
Sam Madden, Anil Shanbhag
