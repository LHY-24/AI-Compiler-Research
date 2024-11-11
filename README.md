# AI-Compiler-Research


## Compiler Toolchain
- [TVM: An Automated End-to-End Optimizing Compiler for Deep Learning](https://www.usenix.org/conference/osdi18/presentation/chen) **OSDI 2018**. [Github Page](https://github.com/apache/tvm). [Document Page](https://tvm.apache.org/). Tianqi Chen, Thierry Moreau, Ziheng Jiang, Lianmin Zheng, Eddie Q. Yan, Haichen Shen, Meghan Cowan, Leyuan Wang, Yuwei Hu, Luis Ceze, Carlos Guestrin, Arvind Krishnamurthy. University of Washington. [Materials](./TVM/)


## Design Space Construction and Exploration


- Auto-tuning and Auto-scheduling
  - [Learning to Optimize Tensor Programs](https://dl.acm.org/doi/10.1145/3306346.3322967) **NeurIPS 2018**. [code](https://github.com/apache/tvm/tree/main/python/tvm/autotvm). Tianqi Chen, Lianmin Zheng, Eddie Q. Yan, Ziheng Jiang, Thierry Moreau, Luis Ceze, Carlos Guestrin, Arvind Krishnamurthy. University of Washington. [Materials](./AutoTVM)
  - [FlexTensor: An Automatic Schedule Exploration and Optimization Framework for Tensor Computation on Heterogeneous System](https://dl.acm.org/doi/10.1145/3373376.3378508) **ASPLOS 2020**. [code](https://github.com/pku-liang/FlexTensor). Size Zheng, Yun Liang, Shuo Wang, Renze Chen, Kaiwen Sheng. Peking University. [Materials](./FlexTensor/)
  - [Enabling Tensor Language Model to Assist in Generating High-Performance Tensor Programs for Deep Learning](https://www.usenix.org/system/files/osdi24-zhai.pdf) **OSDI 2024**. [code](https://github.com/zhaiyi000/tlm). Yi Zhai, Sijia Yang, Keyu Pan, Renwei Zhang, Shuo Liu, Chao Liu, Zichun Ye, Jianmin Ji, Jie Zhao, Yu Zhang*, Yanyong Zhang*. [Metarials](./TLM)



## Dynamic Shape and Control Flow



- Dynamic Shape Operator
  - [Relax: Composable Abstractions for End-to-End Dynamic Machine Learning](http://arxiv.org/abs/2311.02103) **Arxiv 2023**. [code](https://github.com/apache/tvm/tree/main/include/tvm/relax). Ruihang Lai, Junru Shao, Siyuan Feng, Steven S. Lyubomirsky, Bohan Hou, Wuwei Lin, Zihao Ye, Hongyi Jin, Yuchen Jin, Jiawei Liu, Lesheng Jin, Yaxing Cai, Ziheng Jiang, Yong Wu, Sunghyun Park, Prakalp Srivastava, Jared G. Roesch, Todd C. Mowry, Tianqi Chen. [Materials](./Relax/)


## Reference

https://github.com/KnowingNothing/compiler-and-arch?tab=readme-ov-file
