# In-Context-learning-Papers    

![](https://img.shields.io/badge/PRs-welcome-brightgreen) ![Static Badge](https://img.shields.io/badge/In%20context%20Learning-ICL-A9A9A9?style=plastic) ![](https://img.shields.io/github/stars/init-neok/In-Context-learning-Papers?style=social) 

Inspired by the [repository](https://github.com/SinclairCoder/Instruction-Tuning-Papers) about `instruction tuning`, we build this repository to collect papers about In-Context Learning.
* It's my frist time to collect as a repository, so I will try my best to keep it. If you have any suggestions, please feel free to leave an issue.
* What is In-Context Learning? It is an emergent ability which enables language models to perform better just by reading just a few similar demonstrations. 

## Papers
* **Language Models are Few-Shot Learners** `NeurIPS 2020`
  * propose the concept of `In-Context Learning`
  * OpenAI [[link]](https://openai.com/blog/few-shot-learning-of-4k-images/)
  
   *Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam, Girish Sastry, Amanda Askell, Sandhini Agarwal, Ariel Herbert-Voss, Gretchen Krueger, Tom Henighan, Rewon Child, Aditya Ramesh, Daniel M. Ziegler, Jeffrey Wu, Clemens Winter, Christopher Hesse, Mark Chen, Eric Sigler, Mateusz Litwin, Scott Gray, Benjamin Chess, Jack Clark, Christopher Berner, Sam McCandlish, Alec Radford, Ilya Sutskever, Dario Amodei* [[paper]](https://arxiv.org/abs/2005.14165) 2020.5

* **What Makes Good In-Context Examples for GPT-3?** 
  * propose KATE, a method for selecting good in-context examples for GPT-3
  
   *[Jiachang Liu](https://jiachangliu.github.io/), Dinghan Shen, Yizhe Zhang, Bill Dolan, Lawrence Carin, Weizhu Chen* [[paper]](https://arxiv.org/abs/2101.06804) 2021.1

* **Fantastically Ordered Prompts and Where to Find Them: Overcoming Few-Shot Prompt Order Sensitivity** `ACL 2022`
  
   *Yao Lu, Max Bartolo, Alastair Moore, Sebastian Riedel, Pontus Stenetorp* [[paper]](https://aclanthology.org/2022.acl-long.556/) 2021.4

* **MetaICL: Learning to Learn In Context** `NAACL 2022`
  
   *[Sewon Min](https://shmsw25.github.io/), Mike Lewis, Luke Zettlemoyer, Hannaneh Hajishirzi* [[paper]](https://arxiv.org/abs/2110.15943) 2021.10

* **Multitask Prompted Training Enables Zero-Shot Task Generalization** `ICLR 2022`
  
   *Victor Sanh, Albert Webson, Colin Raffel, Stephen H. Bach, Lintang Sutawika, Zaid Alyafeai, Antoine Chaffin, Arnaud Stiegler, Teven Le Scao, Arun Raja, Manan Dey, M Saiful Bari, Canwen Xu, Urmish Thakker, Shanya Sharma Sharma, Eliza Szczechla, Taewoon Kim, Gunjan Chhablani, Nihal Nayak, Debajyoti Datta, Jonathan Chang, Mike Tian-Jian Jiang, Han Wang, Matteo Manica, Sheng Shen, Zheng Xin Yong, Harshit Pandey, Rachel Bawden, Thomas Wang, Trishala Neeraj, Jos Rozen, Abheesht Sharma, Andrea Santilli, Thibault Fevry, Jason Alan Fries, Ryan Teehan, Tali Bers, Stella Biderman, Leo Gao, Thomas Wolf, Alexander M. Rush* [[paper]](https://arxiv.org/abs/2110.08207) 2021.10

* **Meta-learning via Language Model In-context Tuning** `ACL 2022`
  
   *Yanda Chen, Ruiqi Zhong, Sheng Zha, George Karypis, He He* [[paper]](https://aclanthology.org/2022.acl-long.53/) 2021.10

* **An Explanation of In-context Learning as Implicit Bayesian Inference** `ICLR 2022`
  
   *Sang Michael Xie, Aditi Raghunathan, [Percy Liang](https://cs.stanford.edu/~pliang/), Tengyu Ma* [[paper]](https://arxiv.org/abs/2111.02080) 2022.11

* **A Survey on In-context Learning**
  
   *Qingxiu Dong, [Lei Li](https://lilei-nlp.github.io/), Damai Dai, Ce Zheng, [Zhiyong Wu](https://lividwo.github.io/zywu.github.io/), Baobao Chang, Xu Sun, Jingjing Xu, Lei Li and Zhifang Sui* [[paper]](https://arxiv.org/abs/2301.00234) 2022.12

* **Learning To Retrieve Prompts for In-Context Learning** `NAACL 2022`
  * propose the method of `epr`
  * 😝There is a bug in the [page](https://aclanthology.org/2022.naacl-main.191/) of NAACL, if you click the video link on it, you will jump to the video of the introduction of the paper *MetaICL: Learning to Learn In Context*. 
  
   *Ohad Rubin, Jonathan Herzig, Jonathan Berant* [[paper]](https://arxiv.org/abs/2112.08633) 2021.12

* **Calibrate Before Use: Improving Few-shot Performance of Language Models** `ICML 2021`
  
   *Tony Z. Zhao, Eric Wallace, Shi Feng, Dan Klein, Sameer Singh* [[paper]](https://icml.cc/virtual/2021/oral/10186) 2022.2

* **Rethinking the Role of Demonstrations: What Makes In-Context Learning Work?** `EMNLP 2022`
  * zhihu [[link]](https://zhuanlan.zhihu.com/p/664965465) written by me.
  
   *[Sewon Min](https://shmsw25.github.io/), Xinxi Lyu, Ari Holtzman, Mikel Artetxe, Mike Lewis, Hannaneh Hajishirzi, Luke Zettlemoyer* [[paper]](https://arxiv.org/abs/2202.12837) 2022.2

* **Few-Shot Parameter-Efficient Fine-Tuning is Better and Cheaper than In-Context Learning** `NeurIPS 2022`
  * zhihu [[link]](https://zhuanlan.zhihu.com/p/609954679)
  * propose a PEFT method called IA<sup>3</sup>  which is an abbreviation: *I*nfused *A*dapters by Inhibiting and *A*mplifying Inner *A*ctivations
  * propose the method of `T-Few`
  
   *Haokun Liu, Derek Tam, Mohammed Muqeeth, Jay Mohta, Tenghao Huang, Mohit Bansal, Colin Raffel* [[paper]](https://arxiv.org/abs/2205.05638) 2022.5

* **Ground-Truth Labels Matter: A Deeper Look into Input-Label Demonstrations** `EMNLP 2022`
  
   *Kang Min Yoo, Junyeob Kim, Hyuhng Joon Kim, Hyunsoo Cho, Hwiyeol Jo, Sang-Woo Lee, Sang-goo Lee, Taeuk Kim* [[paper]](https://arxiv.org/abs/2205.12685) 2022.5

* **Self-Generated In-Context Learning: Leveraging Auto-regressive Language Models as a Demonstration Generator** `EMNLP 2022`
  
   *Hyuhng Joon Kim, Hyunsoo Cho, Junyeob Kim, Taeuk Kim, Kang Min Yoo, Sang-goo Lee* [[paper]](https://arxiv.org/abs/2206.08082) 2022.5


* **Active Example Selection for In-Context Learning** `EMNLP 2022`
  
   *Yiming Zhang, Shi Feng, Chenhao Tan* [[paper]](https://arxiv.org/abs/2211.04486) 2022.11
* **Teaching Algorithmic Reasoning via In-context Learning** 
  
   *Hattie Zhou, Azade Nova, Hugo Larochelle, Aaron Courville, Behnam Neyshabur, Hanie Sedghi* [[paper]](https://arxiv.org/abs/2211.09066) 2022.11

* **Self-Adaptive In-Context Learning: An Information Compression Perspective for In-Context Example Selection and Ordering** `ACL 2023`
  
   * zhihu [[link]](https://zhuanlan.zhihu.com/p/665852216)
  
   *[Zhiyong Wu](https://lividwo.github.io/zywu.github.io/), Yaoxiang Wang, [Jiacheng Ye](https://jiacheng-ye.github.io/), [Lingpeng Kong](https://ikekonglp.github.io/)* [[paper]](https://arxiv.org/abs/2212.10375) 2022.12
* **Diverse Demonstrations Improve In-context Compositional Generalization** `ACL 2023`
  
   *Itay Levy, Ben Bogin, Jonathan Berant* [[paper]](https://aclanthology.org/2023.acl-long.78.pdf) 2022.12


* **Why Can GPT Learn In-Context? Language Models Implicitly Perform Gradient Descent as Meta-Optimizers** `ICLR 2023`
  
   *Damai Dai, Yutao Sun, Li Dong, Yaru Hao, Shuming Ma, Zhifang Sui, Furu Wei* [[paper]](https://arxiv.org/abs/2212.10559) 2022.12

* **Compositional Exemplars for In-context Learning** `ICML 2023`
  * propose the method of `ceil`
  
   *[Jiacheng Ye](https://jiacheng-ye.github.io/), [Zhiyong Wu](https://lividwo.github.io/zywu.github.io/), Jiangtao Feng, Tao Yu, [Lingpeng Kong](https://ikekonglp.github.io/)* [[paper]](https://arxiv.org/abs/2302.05698) 2023.2

* **Finding Support Examples for In-Context Learning** `EMNLP 2023`
  
   *[Xiaonan Li](https://scholar.google.com/citations?user=ldEcEjEAAAAJ), [Xipeng Qiu](https://xpqiu.github.io/)* [[paper]](https://arxiv.org/abs/2302.13539) 2023.2

* **In-Context Learning with Many Demonstration Examples** 
  
   *Mukai Li, Shansan Gong, Jiangtao Feng, Yiheng Xu, Jun Zhang, Zhiyong Wu, Lingpeng Kong* [[paper]](https://arxiv.org/abs/2302.04931) 2023.2

* **Label Words are Anchors: An Information Flow Perspective for Understanding In-Context Learning** `EMNLP 2023 BEST PAPER AWARD🏆`
  
   Talk from author [[link]](https://event.baai.ac.cn/live/733)
   Zhihu [[link]](https://zhuanlan.zhihu.com/p/439876633)

   *Lean Wang, [Lei Li](https://lilei-nlp.github.io/), Damai Dai, Deli Chen, Hao Zhou, Fandong Meng, Jie Zhou, Xu Sun* [[paper]](https://arxiv.org/abs/2305.14160) 2023.5

* **Coverage-based Example Selection for In-Context Learning** `EMNLP 2023 BEST PAPER AWARD🏆`
  
   *Shivanshu Gupta, Matt Gardner, Sameer Singh* [[paper]](https://arxiv.org/abs/2305.14907) 2023.5

   
* **Unified Demonstration Retriever for In-Context Learning** `ACL 2023`
  
   *Xiaonan Li, Kai Lv, Hang Yan, Tianyang Lin, Wei Zhu, Yuan Ni, Guotong Xie, Xiaoling Wang, [Xipeng Qiu](https://xpqiu.github.io/)* [[paper]](https://arxiv.org/abs/2305.04320) 2023.5

* **PRODIGY: Enabling In-context Learning Over Graphs** `NeurIPS 2023`
  
   *Qian Huang, Hongyu Ren, Peng Chen, Gregor Kržmanc, Daniel Zeng, [Percy Liang](https://cs.stanford.edu/~pliang/), Jure Leskovec* [[paper]](https://arxiv.org/abs/2305.12600) 2023.5

* **In-Context Demonstration Selection with Cross Entropy Difference** `EMNLP 2023`
  
   *Dan Iter, Reid Pryzant, Ruochen Xu, Shuohang Wang, Yang Liu, Yichong Xu, Chenguang Zhu* [[paper]](https://arxiv.org/abs/2305.14726) 2023.5

* **In-Context Learning Creates Task Vectors** `EMNLP 2023`
  
   *Qian Huang, Hongyu Ren, Peng Chen, Gregor Kržmanc, Daniel Zeng, [Percy Liang](https://cs.stanford.edu/~pliang/), Jure Leskovec* [[paper]](https://arxiv.org/abs/2305.12600) 2023.6

* **In-Context Learning with Iterative Demonstration Selection**
  
   *Chengwei Qin, Aston Zhang, Anirudh Dagar, Wenming Ye* [[paper]](https://arxiv.org/abs/2310.09881) 2023.10

* **Exploring the Relationship between In-Context Learning and Instruction Tuning**
  
   *Hanyu Duan, Yixuan Tang, Yi Yang, Ahmed Abbasi, Kar Yan Tam* [[paper]](https://arxiv.org/abs/2311.10367) 2023.11

* **Adapt in Contexts: Retrieval-Augmented Domain Adaptation via In-Context Learning** `EMNLP 2023`
  
   *Quanyu Long, Wenya Wang, Sinno Pan* [[paper]](https://aclanthology.org/2023.emnlp-main.402/) 2023.11

* **Batch-ICL: Effective, Efficient, and Order-Agnostic In-Context Learning** 
  
   *Kaiyi Zhang, Ang Lv, Yuhan Chen, Hansen Ha, Tao Xu, Rui Yan* [[paper]](https://arxiv.org/abs/2401.06469) 2024.01

## Besides Papers
* [blog](https://ai.stanford.edu/blog/understanding-incontext/) by [Sang Michael Xie](https://cs.stanford.edu/~eix/) and [Sewon Min](https://shmsw25.github.io/)
* [blog](https://thegradient.pub/in-context-learning-in-context/) by Daniel Bashir






## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=init-neok/In-Context-learning-Papers&type=Date)](https://star-history.com/#init-neok/In-Context-learning-Papers&Date)
