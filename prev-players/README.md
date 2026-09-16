# Previous players that got acquired 

|                      | Neural Magic               | CentML                           | RadianVector today             |
| -------------------- | -------------------------- | -------------------------------- | ------------------------------ |
| Started as           | CPU inference optimization | ML compiler/runtime optimization | LLM configuration optimization |
| Quantization         | ✅                          | ✅                                | ✅                              |
| Runtime optimization | ✅ DeepSparse/vLLM          | ✅ CServe/vLLM                    | ✅ vLLM currently               |
| Automatic search     | Some                       | **Major part of vision**         | **Major thesis**               |
| Multiple hardware    | ✅                          | ✅                                | Planned                        |
| Multiple runtimes    | Mainly vLLM later          | Increasingly                     | Planned                        |
| Quality measurement  | Model accuracy             | Some                             | **Very explicit**              |
| Latency              | ✅                          | ✅                                | ✅                              |
| Throughput           | ✅                          | ✅                                | ✅                              |
| Cost                 | ✅                          | **✅ strong**                     | Natural next step              |
| Hosted GPUs          | No                         | **Eventually yes**               | No                             |
| Outcome              | Red Hat acquisition        | NVIDIA acquisition               | —                              |


## CentML Vs Radian. Neural Magic acquired by RedHat. CentML acquired by Nvidia 
```
And CentML is much closer to RadianVector than I realized in my previous answer.

There are even conceptual similarities:

CentML:

model + workload + hardware → find an efficient deployment

RadianVector:

model + runtime + quantization + workload + hardware + serving configuration → search configuration space → evaluate speed + wait + capacity + behavior

The distinctive thing you've added is the behavior/quality axis.

That's potentially important because most optimization systems naturally gravitate toward:

$$ \text{minimize cost/latency}\quad\text{subject to performance} $$
```


