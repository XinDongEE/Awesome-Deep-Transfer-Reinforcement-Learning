## Awesome-Deep-Transfer-Reinforcement-Learning
[![author](https://img.shields.io/badge/Author-Xindong-blueviolet.svg)](https://github.com/XinDongEE/Awesome-Deep-Transfer-Reinforcement-Learning)
![license](https://img.shields.io/github/license/XinDongEE/Awesome-Deep-Transfer-Reinforcement-Learning.svg)
![issues](https://img.shields.io/github/issues/XinDongEE/Awesome-Deep-Transfer-Reinforcement-Learning.svg) 
![stars](https://img.shields.io/github/stars/XinDongEE/Awesome-Deep-Transfer-Reinforcement-Learning.svg)
![forks](https://img.shields.io/github/forks/XinDongEE/Awesome-Deep-Transfer-Reinforcement-Learning.svg)
[![Security Status](https://www.murphysec.com/platform3/v31/badge/1703624393803743232.svg)](https://www.murphysec.com/console/report/1703624393619193856/1703624393803743232)

### __Introduction__
Welcome to the Awesome-Deep-Transfer-Reinforcement-Learning library! This project is dedicated to deep transfer reinforcement learning (DTRL), a  field at the intersection of deep learning, reinforcement learning, and transfer learning.

DTRL uses the strengths of deep learning to handle high-dimensional inputs and complex function approximations, the decision-making prowess of reinforcement learning, and the domain adaptability of transfer learning. The core idea is to train an agent in a source domain and enable it to generalize its knowledge and skills to a target domain without requiring extensive training in the target domain.
**This approach is particularly beneficial in scenarios where obtaining training data in the target domain is challenging, a situation frequently encountered in many fields, and notably in power system research（Frequency control，Voltage control, Damping control, Emergency control, et al.), my primary area of focus, where relevant, real-world, and effective data are often scarce.** It is a promising approach to navigate complex learning domains and provide a more feasible way to develop robust optimization strategies for various tasks.

In this library, we curate a rich set of resources including recent papers, recent research advancements, and codebases to facilitate a deeper understanding and application of DTRL. Whether you are a researcher, a developer, or an enthusiast eager to delve into this exciting field, this library is for you.

### __Contents__
- __Reward Shaping__
	- **[1]**   Z. Zhu, K. Lin, A. K. Jain and J. Zhou, "[Transfer Learning in Deep Reinforcement Learning: A Survey](https://ieeexplore.ieee.org/abstract/document/10172347),"   _IEEE Transactions on Pattern Analysis and Machine Intelligence_, doi: 10.1109/TPAMI.2023.3292075.
	- **[2]**   T. Brys, A. Harutyunyan, M. E. Taylor, and A. Nowe, "[Policy transfer using reward shaping](https://dl.acm.org/doi/10.5555/2772879.2772905),"   _ICAAMS_,  2015.
	- **[3]**   Vecerik, M. "[Leveraging Demonstrations for Deep Reinforcement Learning on Robotics Problems with Sparse Rewards](https://arxiv.org/abs/1707.08817),"   _arXiv preprint_: 1707.08817, 2017.
  	- **[4]**   A. C. Tenorio-Gonzalez, E. F. Morales, and L. Vilasenor-Pineda, "[Dynamic reward shaping: Training a robot by voice](https://link.springer.com/chapter/10.1007/978-3-642-16952-6_49)," _Advances in Artificial Intelligence_,   IBERAMIA, 2010.
	- **[5]**   P.-H. Su, D. Vandyke, M. Gasic, N. Mrksic, T.-H.Wen, and S. Young, "[Reward shaping with recurrent neural networks for speeding up on-line policy learning in spoken dialogue systems](https://arxiv.org/abs/1508.03391),"  _arXiv preprint_: 1508.03391, 2015.
	- **[6]**   X. V. Lin, R. Socher, and C. Xiong, "[Multi-hop knowledge graph reasoning with reward shaping](https://arxiv.org/abs/1808.10568),"  _arXiv preprint_: 1808.10568, 2018..
	- **[7]**   S. Devlin, L. Yliniemi, D. Kudenko, and K. Tumer, "[Potential-based difference rewards for multiagent reinforcement learning](https://dl.acm.org/doi/10.5555/2615731.2615761#:~:text=Difference%20rewards%20and%20potential-ased%20reward%20shaping%20can%20both,capture%20an%20agent%27s%20contribution%20to%20the%20system%27s%20performance.),"  _ICAAMS_: 2014.
	- **[8]**   M. Grzes and D. Kudenko, "[Learning shaping rewards in model-based reinforcement learning](https://eecs.wsu.edu/~taylorm/ALA09/7.pdf),"  _Proc. AAMAS Workshop on Adaptive Learning Agents_, 2009.

- __Learning from Demonstarts__
	- **[1]**   X. Zhang and H. Ma, "[Pretraining deep actor-critic reinforcement learning algorithms with expert demonstrations](https://arxiv.org/abs/1801.10459),"  _arXiv preprint_:1801.10459, 2018.
	- **[2]**   Silver, D., Huang, A., Maddison, C. et al, "[Mastering the game of Go with deep neural networks and tree search](https://www.nature.com/articles/nature16961#citeas),"  _Nature_ 529, 484–489 (2016). https://doi.org/10.1038/nature16961.
  	- **[3]**   T. Hester, M. Vecerik, O. Pietquin, M. Lanctot, T. Schaul, B. Piot, D. Horgan, J. Quan, A. Sendonaris, I. Osband et al., "[Deep q-learning from demonstrations](https://arxiv.org/abs/1704.03732),"  _AAAI_, 2018
	- **[4]**   A. Nair, B. McGrew, M. Andrychowicz, W. Zaremba, and P. Abbeel, "[Overcoming exploration in reinforcement learning with demonstrations](https://arxiv.org/abs/1709.10089),"  _IEEE International Conference on Robotics and Automation (ICRA)_, 2018.
	- **[5]**   Yaser Keneshloo, Naren Ramakrishnan, Chandan K. Reddy, "[Deep Transfer Reinforcement Learning for Text Summarization](https://arxiv.org/abs/1810.06667),"   _arXiv preprint_:1810.06667. ---[**[Code Available](https://github.com/yaserkl/TransferRL)**].
   	- **[6]**   Lian, R., H. Tan, J. Peng, Q. Li, Y. Wu, "[Cross-type transfer for deep reinforcement learning based hybrid electric vehicle energy management](https://ieeexplore.ieee.org/abstract/document/9105110),"  _IEEE Transactions on Vehicular Technology_, 2020. ---[**[Code Available](https://github.com/lryz0612/Transfer_DRL_EMS)**].
   	- **[7]**   Tianpei Yang, Jianye Hao, Zhaopeng Meng, "[Efficient Deep Reinforcement Learning via Adaptive Policy Transfer](https://arxiv.org/abs/2002.08037),"   _arXiv preprint_:2002.08037. ---[**[Code Available](https://github.com/tianpeiyang/PTF_code)**].
   	- **[7]**   Yang, Tianpei and Wang, Weixun and Tang, Hongyao, "[An Efficient Transfer Learning Framework for Multiagent Reinforcement Learning](https://openreview.net/pdf?id=GAiM0RXrMfF),"   _Advances in Neural Information Processing Systems_:34, 2021. ---[**[Code Available](https://github.com/tianpeiyang/MAPTF_code)**].

- __Inter-Task Mapping__
	- **[1]**   A. Gupta, C. Devin, Y. Liu, P. Abbeel, and S. Levine, "[Learning invariant feature spaces to transfer skills with reinforcement learning](https://arxiv.org/abs/1703.02949),"  _ICLR_, 2017.
	- **[2]**   V. Badrinarayanan, A. Kendall, and R. Cipolla, "[Segnet: A deep convolutional encoder-decoder architecture for image segmentation](https://ieeexplore.ieee.org/document/7803544),"  _IEEE transactions on pattern analysis and machine ntelligence_, 2017
	- **[3]**   H. B. Ammar, E. Eaton, P. Ruvolo, and M. E. Taylor, "[Unsupervised cross-domain transfer in policy gradient reinforcement learning via manifold alignment](https://dl.acm.org/doi/10.5555/2886521.2886669),"  _AAAI_, 2015.
	- **[4]**   H. B. Ammar, K. Tuyls, M. E. Taylor, K. Driessens, and G. Weiss, "[Reinforcement learning transfer via sparse coding](https://dl.acm.org/doi/10.5555/2343576.2343631),"  _ICAAMS_, 2012.
	- **[5]**   J. Oh, S. Singh, H. Lee, and P. Kohli, "[Zero-shot task generalization with multi-task deep reinforcement learning](https://arxiv.org/abs/1706.05064),"  _Proc. 34th Int. Conf. Mach. Learn_, vol. 70, 2017, pp. 2661–2670.
	- **[6]**   Parisotto E, Ba JL, Salakhutdinov R, "[Actor-mimic: Deep multitask and transfer reinforcement learning](https://arxiv.org/abs/1511.06342),"  _arXiv preprint_:1511.06342. 2015 Nov 19.

- __Representation Transfer__
	- **[1]**   J. C. Petangoda, S. Pascual-Diaz, V. Adam, P. Vrancx, and J. Grau-Moya, "[Disentangled skill embeddings for reinforcement learning](https://arxiv.org/abs/1906.09223),"  _arXiv preprint_:1906.09223, 2019.
	- **[2]**   C. Finn, P. Abbeel, and S. Levine, "[Model-agnostic meta-learning for fast adaptation of deep networks](https://arxiv.org/abs/1703.03400),"  _ICML_, 2017.
	- **[3]**   Y. Deng, F. Bao, Y. Kong, Z. Ren and Q. Dai, "[Deep Direct Reinforcement Learning for Financial Signal Representation and Trading](https://ieeexplore.ieee.org/document/7407387),"  _IEEE Transactions on Neural Networks and Learning Systems_, vol. 28, no. 3, pp. 653-664, March 2017.
	- **[4]**   F. -X. Devailly, D. Larocque and L. Charlin, "[IG-RL: Inductive Graph Reinforcement Learning for Massive-Scale Traffic Signal Control](https://ieeexplore.ieee.org/document/9405489),"  _IEEE Transactions on Intelligent Transportation Systems_, vol. 23, no. 7, pp. 7496-7507, July 2022,. 
	- **[5]**   I. Higgins et al., "[Darla: Improving zero-shot transfer in reinforcement learning](https://arxiv.org/abs/1707.08475),"  _Proc. 34th Int. Conf. Mach. Learn_, vol. 70, 2017, pp. 1480–1490. 
 	- **[6]**   Q. Yan, S. Guo, D. Chen, Z. Yang and F. Chen, "[Transferable Environment Model With Disentangled Dynamics](https://ieeexplore.ieee.org/document/8755923),"  _IEEE Access_, vol. 7, pp. 106848-106860, 2019.
 	- **[7]**   Islam, T., Abid, D.M.H., Rahman, T., Zaman, Z., Mia, K., Hossain, R. (2023), "[Transfer Learning in Deep Reinforcement Learning](https://link.springer.com/chapter/10.1007/978-981-19-1607-6_13#editor-information),"  _Proceedings of Seventh International Congress on Information and Communication Technology. Lecture Notes in Networks and Systems_, vol 447. Springer, Singapore.

### Acknowledgement
Note: We will keep updating this __Library__. If you have proposed advanced and awesome models, welcome to send your paper/code link to us or raise a pull request. We will add them to this repo and update the __Library__ as soon as possible.  
If you have any problems or contributions, please feel free to contact us on our email: xindong_scu@qq.com.
