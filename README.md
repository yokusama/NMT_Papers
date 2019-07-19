# NMT_Papers (Update Continuously)

## Some Papers about NMT (Neural Machine Translation)

Some papers I **have read** about NMT.

Machine translation is a very interesting research direction! Hope you can fine something you need(like)!

If you are interested in machine translation and have any questions, **please feel free to contact me!**

* [Must Reads](#mustreads)
* [Analysis](#analysis)
* [Attention Mechanism](#attention)
* [Model Improvement](#modelimprovement)
* [Discourse and Document-level NMT](#document-level)
* [Objective Function](#objectivefunction)
* [Robustness](#robustness)
* [Data Augmentation](#data)
* [Low Source](#lowsource)
* [Domain adaptation](#domainadaptation)
* [Multi-lingual/source/task NMT](#multilingual)
* [Incorporate External Knowledge](#externalknowledge)
* [Open Vocabulary Problem](#oov)
* [Evaluation](#evaluation)
* [Unsupervised NMT](#unsupervised)

<h2 id="mustreads">Must Reads</h2> 

* **Sequence to Sequence Learning with Neural Networks.**
*Ilya Sutskever, Oriol Vinyals, Quoc V. Le.* NIPS 2014. [paper](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf)

* **Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation.**
*Kyunghyun Cho, Bart van Merrienboer, Caglar Gulcehre, Dzmitry Bahdanau, Fethi Bougares, Holger Schwenk, Yoshua Bengio.* EMNLP 2014. [paper](https://www.aclweb.org/anthology/D14-1179)

* **Neural Machine Translation by Jointly Learning to Align and Translate.**
*Dzmitry Bahdanau, Kyunghyun Cho, Yoshua Bengio.* ICLR 2015. [paper](https://arxiv.org/pdf/1409.0473.pdf)

* **Effective Approaches to Attention-based Neural Machine Translation.**
*Minh-Thang Luong, Hieu Pham, Christopher D. Manning.* EMNLP 2015. [paper](http://aclweb.org/anthology/D15-1166)

* **Convolutional Sequence to Sequence Learning.**
*Jonas Gehring, Michael Auli, David Grangier, Denis Yarats, Yann N. Dauphin.*  2017.  [paper](https://arxiv.org/pdf/1705.03122.pdf)

* **Attention Is All You Need.**
*Mia Xu Chen, Orhan Firat, Ankur Bapna, Melvin Johnson, Wolfgang Macherey, George Foster, Llion Jones, Niki Parmar, Mike Schuster, Zhifeng Chen, Yonghui Wu, Macduff Hughes.* ACL 2018.  [paper](https://papers.nips.cc/paper/7181-attention-is-all-you-need.pdf)

* **BLEU: a Method for Automatic Evaluation of Machine Translation.**
*Kishore Papineni, Salim Roukos, Todd Ward, Wei-Jing Zhu.* ACL 2002.  [paper](https://www.aclweb.org/anthology/P02-1040.pdf)

* **Neural Machine Translation of Rare Words with Subword Units.**
*Rico Sennrich and Barry Haddow and Alexandra Birch.* ACL 2016.  [paper](http://www.aclweb.org/anthology/P16-1162)


<h2 id="analysis">Analysis:</h2> 

* **Does String-Based Neural MT Learn Source Syntax?.**
*Xing Shi, Inkit Padhi, and Kevin Knight.* EMNLP 2016.  [paper](http://aclweb.org/anthology/D16-1159)

* **What do Neural Machine Translation Models Learn about Morphology?**
*Yonatan Belinkov, Nadir Durrani, Fahim Dalvi, Hassan Sajjad, James Glass.* ACL 2017.  [paper](https://arxiv.org/pdf/1704.0347*pdf)

* **The Lazy Encoder: A Fine-Grained Analysis of the Role of Morphology in Neural Machine Translation.**
*Arianna Bisazza, Clara Tump.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1313)

* **Evaluating Layers of Representation in Neural Machine Translation on Part-of-Speech and Semantic Tagging Tasks.**
*Yonatan Belinkov, Lluís Màrquez, Hassan Sajjad, Nadir Durrani, Fahim Dalvi, James Glass.* ICJNLP 2017.  [paper](http://aclweb.org/anthology/I17-1001)

* **On the Evaluation of Semantic Phenomena in Neural Machine Translation Using Natural Language Inference**
*Adam Poliak, Yonatan Belinkov, James Glass, Benjamin Van Durme.* NAACL 2018.  [paper](http://www.aclweb.org/anthology/N18-2082)

* **Beyond Error Propagation in Neural Machine Translation: Characteristics of Language Also Matter.**
*Lijun Wu, Xu Tan, Di He, Fei Tian, Tao Qin, Jianhuang Lai, Tie-Yan Liu.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1396)

* **When and Why are Pre-trained Word Embeddings Useful for Neural Machine Translation?**
*Ye Qi, Devendra Singh Sachan, Matthieu Felix, Sarguna Janani Padmanabhan, Graham Neubig.* NAACL 2018.  [paper](http://www.aclweb.org/anthology/N18-2084)

* **A Comparison of Transformer and Recurrent Neural Networks on Multilingual Neural Machine Translation.**
*Surafel M. Lakew, Mauro Cettolo, Marcello Federico.* COLING 2018.  [paper](http://aclweb.org/anthology/C18-1054)

* **Context and Copying in Neural Machine Translation.**
*Rebecca Knowles, Philipp Koehn.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1339)

* **Getting Gender Right in Neural Machine Translation.**
*Eva Vanmassenhove, Christian Hardmeier, Andy Way.* EMNLP 2018.  [paper](http://www.aclweb.org/anthology/D18-1334)

* **On the Impact of Various Types of Noise on Neural Machine Translation.**
*Huda Khayrallah, Philipp Koehn.* WNMT 2018.  [paper](http://www.aclweb.org/anthology/W18-2709)

* **Visualizing and Understanding Neural Machine Translation.**
*Yanzhuo Ding, Yang Liu, Huanbo Luan, Maosong Sun.* ACL 2017.  [paper](http://aclweb.org/anthology/P17-1106)

* **Massive Exploration of Neural Machine Translation Architectures.**
*Denny Britz, Anna Goldie, Minh-Thang Luong, Quoc Le.* ACL 2017.  [paper](https://www.aclweb.org/anthology/D17-1151)

* **One Size Does Not Fit All: Comparing NMT Representations of Different Granularities.**
*Nadir Durrani, Fahim Dalvi, Hassan Sajjad, Yonatan Belinkov, Preslav Nakov.* NAACL 2019.  [paper](https://www.aclweb.org/anthology/papers/N/N19/N19-1154/)

* **A Call for Prudent Choice of Subword Merge Operations in Neural Machine Translation.**
*Shuoyang Ding, Adithya Renduchintala, Kevin Duh.*  MT Summit 2019.  [paper](https://arxiv.org/pdf/1905.10453.pdf)

* **Probing the Need for Visual Context in Multimodal Machine Translation.**
*Ozan Caglayan, Pranava Madhyastha, Lucia Specia, Loïc Barrault.* NAACL 2019.  [paper](https://www.aclweb.org/anthology/N19-1422)

### Attention Analysis

* **An Analysis of Encoder Representations in Transformer-Based Machine Translation.**
*Alessandro Raganato and Jorg Tiedemann.* EMNLP Worshopp BlackboxNLP 2018.  [paper](http://aclweb.org/anthology/W18-5431)

* **How Much Attention Do You Need? A Granular Analysis of Neural Machine Translation Architectures.**
*Tobias Domhan.* ACL 2018.  [paper](http://aclweb.org/anthology/P18-1167)

* **Why Self-Attention? A Targeted Evaluation of Neural Machine Translation Architectures.**
*Gongbo Tang, Mathias Müller, Annette Rios, Rico Sennrich.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1458)

* **Assessing the Ability of Self-Attention Networks to Learn Word Order.**
*Baosong Yang, Longyue Wang, Derek F. Wong, Lidia S. Chao, Zhaopeng Tu.* ACL 2019.  [paper](https://arxiv.org/pdf/1906.00592.pdf)

* **Analyzing Multi-Head Self-Attention: Specialized Heads Do the Heavy Lifting, the Rest Can Be Pruned.**
*Elena Voita, David Talbot, Fedor Moiseev, Rico Sennrich, Ivan Titov.* ACL 2019.  [paper](https://arxiv.org/pdf/1905.09418.pdf)

* **Are Sixteen Heads Really Better than One?.**
*Paul Michel, Omer Levy, Graham Neubig.* Arxiv 2019.  [paper](https://arxiv.org/pdf/1905.10650.pdf)

<h2 id="attention">Attention Mechanism:</h2> 

#### RNN seq2seq:

* **Interactive Attention for Neural Machine Translation.**
*Fandong Meng, Zhengdong Lu, Hang Li, Qun Liu.* COLING 2016.  [paper](http://aclweb.org/anthology/C16-1205)

* **Neural Machine Translation with Recurrent Attention Modeling.**
*Zichao Yang, Zhiting Hu, Yuntian Deng, Chris Dyer, Alex Smola.* EACL 2017.  [paper](http://www.aclweb.org/anthology/E17-2061)

* **Neural Machine Translation with Deep Attention.**
*Biao Zhang, Deyi Xiong, Jinsong Su.* IEEE 2018.  [paper](https://ieeexplore.ieee.org/document/8493282)

* **Learning When to Concentrate or Divert Attention: Self-Adaptive Attention Temperature for Neural Machine Translation.**
*Junyang Lin, Xu Sun, Xuancheng Ren, Muyu Li, Qi Su.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1331)

* **Surprisingly Easy Hard-Attention for Sequence to Sequence Learning.**
*Shiv Shankar, Siddhant Garg, Sunita Sarawagi.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1065)

* **Sparse and Constrained Attention for Neural Machine Translation.**
*Chaitanya Malaviya, Pedro Ferreira, André F. T. Martins.* ACL 2018.  [paper](http://aclweb.org/anthology/P18-2059)

* **Attention Focusing for Neural Machine Translation by Bridging Source and Target Embeddings.**
*Shaohui Kuang, Junhui Li, António Branco, Weihua Luo, Deyi Xiong.* ACL 2018.  [paper](http://aclweb.org/anthology/P18-1164)

* **Word Attention for Sequence to Sequence Text Understanding.**
*Lijun Wu, Fei Tian, Li Zhao, Jianhuang Lai, Tie-Yan Liu.* AAAI 2018.  [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/11/word_attention_camera_ready.pdf)

* **Attention-via-Attention Neural Machine Translation.**
*Shenjian Zhao, Zhihua Zhang.* AAAI 2018.  [paper](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16534/15733)

* **Combining Character and Word Information in Neural Machine Translation Using a Multi-Level Attention.**
*Huadong Chen, Shujian Huang†, David Chiang, Xinyu Dai, Jiajun Chen.* NAACL 2018.  [paper](http://www.aclweb.org/anthology/N18-1116)

* **Target Foresight based Attention for Neural Machine Translation.**
*Xintong Li, Lemao Liu, Zhaopeng Tu, Shuming Shi, Max Meng.* NAACL 2018.  [paper](http://www.aclweb.org/anthology/N18-1125)

* **Neural Machine Translation with Decoding-History Enhanced Attention.**
*Mingxuan Wang, Jun Xie, Zhixing Tan, Jinsong Su, Deyi Xiong, Chao bian.* COLING 2018.  [paper](http://aclweb.org/anthology/C18-1124)

#### Transformer:

* **Accelerating Neural Transformer via an Average Attention Network.**
*Biao Zhang, Deyi Xiong, Jinsong Su.* ACL 2018.  [paper](http://aclweb.org/anthology/P18-1166)

* **Self-Attention with Relative Position Representations.**
*Peter Shaw, Jakob Uszkoreit, Ashish Vaswani.* ACL 2018.  [paper](http://aclweb.org/anthology/N18-2074)

* **Modeling Localness for Self-Attention Networks.**
*Baosong Yang, Zhaopeng Tu, Derek F. Wong, Fandong Meng, Lidia S. Chao, Tong Zhang.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1475)

* **On The Alignment Problem In Multi-Head Attention-Based Neural Machine Translation.**
*Tamer Alkhouli, Gabriel Bretschner, Hermann Ney.* WMT 2018.  [paper](http://aclweb.org/anthology/W18-6318)

* **Multi-Head Attention with Disagreement Regularization.**
*Jian Li, Zhaopeng Tu, Baosong Yang, Michael R. Lyu, Tong Zhang.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1317)

* **Information Aggregation for Multi-Head Attention with Routing-by-Agreement.**
*Jian Li, Baosong Yang, Zi-Yi Dou, Xing Wang, Michael R. Lyu, Zhaopeng Tu.* NAACL 2019.  [paper](https://arxiv.org/pdf/1904.03100.pdf)

* **Pay Less Attention with Lightweight and Dynamic Convolutions.**
*Felix Wu, Angela Fan, Alexei Baevski, Yann N. Dauphin, Michael Auli.* ICLR 2019.  [paper](https://openreview.net/pdf?id=SkVhlh09tX)

* **Convolutional Self-Attention Network.**
*Baosong Yang, Longyue Wang, Derek F. Wong, Lidia S. Chao, Zhaopeng Tu.* NAACL 2019.  [paper](https://arxiv.org/pdf/1904.03107.pdf)

* **Context-Aware Self-Attention Networks.**
*Baosong Yang, Jian Li, Derek Wong, Lidia S. Chao, Xing Wang, Zhaopeng Tu.* AAAI 2019.  [paper](https://arxiv.org/pdf/1902.05766.pdf)

* **Widening the Representation Bottleneck in Neural Machine Translation with Lexical Shortcuts.**
*Denis Emelin, Ivan Titov, Rico Sennrich.* WMT 2019.  [paper](https://arxiv.org/pdf/1906.12284.pdf)


<h2 id="modelimprovement">Model Improvement:</h2> 

#### RNN seq2seq:

* **Google's Neural Machine Translation System: Bridging the Gap between Human and Machine Translation.**
*Yonghui Wu, Mike Schuster, Zhifeng Chen, Quoc V. Le, Mohammad Norouzi, Wolfgang Macherey, Maxim Krikun, Yuan Cao, Qin Gao, Klaus Macherey, Jeff Klingner, Apurva Shah, Melvin Johnson, Xiaobing Liu, Łukasz Kaiser, Stephan Gouws, Yoshikiyo Kato, Taku Kudo, Hideto Kazawa, Keith Stevens, George Kurian, Nishant Patil, Wei Wang, Cliff Young, Jason Smith, Jason Riesa, Alex Rudnick, Oriol Vinyals, Greg Corrado, Macduff Hughes, Jeffrey Dean.* 2016.  [paper](https://arxiv.org/pdf/1609.08144.pdf)

* **You May Not Need Attention.**
*Ofir Press, Noah A. Smith.*  2018.  [paper](https://arxiv.org/pdf/1810.13409.pdf)

* **Context Gates for Neural Machine Translation.**
*Zhaopeng Tu, Yang Liu, Zhengdong Lu, Xiaohua Liu, Hang Li.* TACL 2017.  [paper](http://www.aclweb.org/anthology/Q17-1007)

* **A Context-Aware Recurrent Encoder for Neural Machine Translation.**
*Biao Zhang, Deyi Xiong, Jinsong Su, Hong Duan.*   IEEE/ACM Transactions on Audio, Speech, and Language Processing 2017.  [paper](https://ieeexplore.ieee.org/document/8031316)

* **Context-Dependent Word Representation for Neural Machine Translation.**
*Heeyoul Choi, Kyunghyun Cho, Yoshua Bengio.*   [paper](https://arxiv.org/pdf/1607.00578.pdf)

* **Handling Homographs in Neural Machine Translation.**
*Frederick Liu, Han Lu, Graham Neubig.* NAACL 2018.  [paper](http://aclweb.org/anthology/N18-1121)

* **Improving Neural Machine Translation by Incorporating Hierarchical Subword Features.**
*Makoto Morishita, Jun Suzuki and Masaaki Nagata.*  COLING 2018.  [paper](https://www.aclweb.org/anthology/C18-1052)

* **Compositional Representation of Morphologically-Rich Input for Neural Machine Translation.**
*Duygu Ataman, Marcello Federico.*  ACL 2018.  [paper](http://www.aclweb.org/anthology/P18-2049)

* **Refining Source Representations with Relation Networks for Neural Machine Translation.**
*Wen Zhang, Jiawei Hu, Yang Feng, Qun Liu.*  NAACL 2018.  [paper](http://www.aclweb.org/anthology/N18-1117)

* **Improving Lexical Choice in Neural Machine Translation.**
*Toan Q. Nguyen, David Chiang.*  ACL 2018.  [paper](http://aclweb.org/anthology/N18-1031)

* **Neural Machine Translation with Word Predictions.**
*Rongxiang Weng, Shujian Huang, Zaixiang Zheng, Xinyu Dai, Jiajun Chen.*  EMNLP 2017.  [paper](https://www.aclweb.org/anthology/D17-1013)

* **ReWE: Regressing Word Embeddings for Regularization of Neural Machine Translation Systems.**
*Inigo Jauregi Unanue, Ehsan Zare Borzeshi, Nazanin Esmaili, Massimo Piccardi.*  NAACL 2019.  [paper](https://arxiv.org/pdf/1904.02461.pdf)

* **Dense Information Flow for Neural Machine Translation.**
*Yanyao Shen, Xu Tan, Di He, Tao Qin, Tie-Yan Liu.*  COLING 2018.  [paper](http://aclweb.org/anthology/C18-1110)

* **Adaptive Weighting for Neural Machine Translation.**
*Yachao Li1, Junhui Li, Min Zhang.*  COLING 2018.  [paper](http://aclweb.org/anthology/C18-1257)

* **Multi-channel Encoder for Neural Machine Translation.**
*Hao Xiong, Zhongjun He, Xiaoguang Hu, Hua Wu.*  AAAI 2018.  [paper](https://arxiv.org/pdf/1712.02109.pdf)

* **Towards Two-Dimensional Sequence to Sequence Model in Neural Machine Translation.**
*Parnia Bahar, Christopher Brix, Hermann Ney.*  EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1335)

* **Modeling Past and Future for Neural Machine Translation.**
*Zaixiang Zheng, Hao Zhou, Shujian Huang, Lili Mou, Xinyu Dai, Jiajun Chen, Zhaopeng Tu.*  TACL 2018.  [paper](http://aclweb.org/anthology/Q18-1011)

* **Self-Attentive Residual Decoder for Neural Machine Translation.**
*Lesly Miculicich Werlen, Nikolaos Pappas, Dhananjay Ram, Andrei Popescu-Belis.*  NAACL 2018.  [paper](http://aclweb.org/anthology/N18-1124)

* **Modeling Coverage for Neural Machine Translation.**
*Zhaopeng Tu, Zhengdong Lu, Yang Liu, Xiaohua Liu, Hang Li.*  ACL 2016.  [paper](http://www.aclweb.org/anthology/P16-1008)

* **A Simple and Effective Approach to Coverage-Aware Neural Machine Translation.**
*Yanyang Li, Tong Xiao, Yinqiao Li, Qiang Wang, Changming Xu, Jingbo Zhu.*  ACL 2018.  [paper](http://aclweb.org/anthology/P18-2047)

* **Simplifying Neural Machine Translation with Addition-Subtraction Twin-Gated Recurrent Networks.**
*Biao Zhang, Deyi Xiong, Jinsong Su, Qian Lin, Huiji Zhang.*  EMNLP 2018.  [paper](https://arxiv.org/pdf/1905.13324.pdf)

* **A Lightweight Recurrent Network for Sequence Modeling.**
*Biao Zhang, Rico Sennrichg.*  ACL 2019.  [paper](http://aclweb.org/anthology/D18-1459)

* **Chunk-Based Bi-Scale Decoder for Neural Machine Translation.**
*Hao Zhou, Zhaopeng Tu, Shujian Huang, Xiaohua Liu, Hang Li, Jiajun Chen.*  ACL 2017.  [paper](https://www.aclweb.org/anthology/P17-2092)

* **Chunk-based Decoder for Neural Machine Translation.**
*Shonosuke Ishiwatari, Jingtao Yao, Shujie Liu, Mu Li, Ming Zhou, Naoki Yoshinaga, Masaru Kitsuregawa, Weijia Jia.*  ACL 2017.  [paper](https://aclweb.org/anthology/P17-1174)

* **Deconvolution-Based Global Decoding for Neural Machine Translation.**
*Junyang Lin, Xu Sun, Xuancheng Ren, Shuming Ma, Jinsong Su, Qi Su.*  COLING 2018.  [paper](https://www.aclweb.org/anthology/C18-1276)

* **Asynchronous Bidirectional Decoding for Neural Machine Translation.**
*Xiangwen Zhang, Jinsong Su, Yue Qin, Yang Liu, Rongrong Ji, Hongji Wang.*  AAAI 2018.  [paper](https://arxiv.org/pdf/1801.05122.pdf)

* **Deliberation Networks: Sequence Generation Beyond One-Pass Decoding.**
*Yingce Xia, Fei Tian, Lijun Wu, Jianxin Lin, Tao Qin, Nenghai Yu, Tie-Yan Liu.*  NIPS 2017.  [paper](https://papers.nips.cc/paper/6775-deliberation-networks-sequence-generation-beyond-one-pass-decoding.pdf)

* **Dual Learning for Machine Translation.**
*Yingce Xia, Di He, Tao Qin, Liwei Wang, Nenghai Yu, Tie-Yan Liu, Wei-Ying Ma.*  NIPS 2016.  [paper](https://papers.nips.cc/paper/6469-dual-learning-for-machine-translation.pdf)

* **Identifying and Controlling Important Neurons in Neural Machine Translation.**
*Anthony Bau, Yonatan Belinkov, Hassan Sajjad, Nadir Durrani, Fahim Dalvi, James Glass.*  ICLR 2019.  [paper](https://openreview.net/pdf?id=H1z-PsR5KX)

##### Deeper 

* **Deep Recurrent Models with Fast-Forward Connections for Neural Machine Translation.**
*Jie Zhou, Ying Cao, Xuguang Wang, Peng Li, Wei Xu.*  TACL 2016.  [paper](https://www.aclweb.org/anthology/Q16-1027)

* **Deep Architectures for Neural Machine Translation.**
*Antonio Valerio Miceli Barone, Jindřich Helcl, Rico Sennrich, Barry Haddow, Alexandra Birch.*  WMT 2017.  [paper](http://www.statmt.org/wmt17/pdf/WMT10.pdf)

* **Deep Neural Machine Translation with Linear Associative Unit.**
*Mingxuan Wang, Zhengdong Lu, Jie Zhou, Qun Liu.*  ACL 2017.  [paper](http://www.aclweb.org/anthology/P17-1013)

* **DTMT: A Novel Deep Transition Architecture for Neural Machine Translation.**
*Fandong Meng, Jinchao Zhang.*  AAAI 2019.  [paper](https://arxiv.org/pdf/1812.07807.pdf)

#### Transformer:

* **Universal Transformers.**
*Mostafa Dehghani, Stephan Gouws, Oriol Vinyals, Jakob Uszkoreit, Łukasz Kaiser.*  [paper](https://arxiv.org/pdf/1807.03819.pdf)

* **Layer-Wise Coordination between Encoder and Decoder for Neural Machine Translation.**
*He Tianyu, Tan Xu, Xia Yingce, He Di, Qin Tao, Chen Zhibo, Liu Tie-Yan.* NIPS 2018.  [paper](http://papers.nips.cc/paper/8019-layer-wise-coordination-between-encoder-and-decoder-for-neural-machine-translation.pdf)

* **Tied Transformers: Neural Machine Translation with Shared Encoder and Decoder.**
*Yingce Xia, Tianyu He, Xu Tan, Fei Tian, Di He and Tao Qin.*  AAAI 2019.  [paper](https://taoqin.github.io/papers/tiedT.AAAI2019.pdf)

* **The Best of Both Worlds: Combining Recent Advances in Neural Machine Translation.**
*Mia Xu Chen, Orhan Firat, Ankur Bapna, Melvin Johnson, Wolfgang Macherey, George Foster, Llion Jones, Niki Parmar, Mike Schuster, Zhifeng Chen, Yonghui Wu, Macduff Hughes.* ACL 2018.  [paper](http://aclweb.org/anthology/P18-1008)

* **Modeling Recurrence for Transformer.**
*Jie Hao, Xing Wang, Baosong Yang, Longyue Wang, Jinfeng Zhang, Zhaopeng Tu.* NAACL 2019.  [paper](https://arxiv.org/pdf/1904.03092.pdf)

* **Exploiting Sentential Context for Neural Machine Translation.**
*Xing Wang, Zhaopeng Tu, Longyue Wang, Shuming Shi.* ACL 2019.  [paper](https://arxiv.org/pdf/1906.01268.pdf)

* **Multi-layer Representation Fusion for Neural Machine Translation.**
*Qiang Wang, Fuxue Li, Tong Xiao, Yanyang Li, Yinqiao Li, Jingbo Zhu.* COLING 2018.  [paper](http://aclweb.org/anthology/C18-1255)

* **Exploiting Deep Representations for Neural Machine Translation.**
*Zi-Yi Dou, Zhaopeng Tu, Xing Wang, Shuming Shi, Tong Zhang.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1457)

* **Dynamic Layer Aggregation for Neural Machine Translation with Routing-by-Agreement.**
*Zi-Yi Dou, Zhaopeng Tu, Xing Wang, Shuming Shi, Tong Zhang.* AAAI 2019.  [paper](https://www.aaai.org/Papers/AAAI/2019/AAAI-DouZ.3868.pdf)

* **Lost in Machine Translation: A Method to Reduce Meaning Loss.**
*Reuben Cohn-Gordon, Noah Goodman.* NAACL 2019.  [paper](https://arxiv.org/pdf/1902.09514.pdf)

##### Deeper:

* **Training Deeper Neural Machine Translation Models with Transparent Attention.**
*Ankur Bapna, Mia Xu Chen, Orhan Firat, Yuan Cao, Yonghui Wu.* EMNLP 2018.  [paper](https://aclweb.org/anthology/D18-1338)

* **Learning Deep Transformer Models for Machine Translation.**
*Qiang Wang, Bei Li, Tong Xiao, Jingbo Zhu, Changliang Li, Derek F. Wong, Lidia S. Chao.* ACL 2019.  [paper](https://arxiv.org/pdf/1906.01787.pdf)

* **Depth Growing for Neural Machine Translation.**
*Lijun Wu, Yiren Wang, Yingce Xia, Fei Tian, Fei Gao, Tao Qin, Jianhuang Lai, Tie-Yan Liu.* ACL 2019.  [paper](https://arxiv.org/pdf/1907.01968.pdf)

##### Efficiency:

* **Sharing Attention Weights for Fast Transformer.**
*Tong Xiao, Yinqiao Li, Jingbo Zhu, Zhengtao Yu, Tongran Liu.* IJCAI 2019.  [paper](https://arxiv.org/pdf/1906.11024.pdf)

* **Shared-Private Bilingual Word Embeddings for Neural Machine Translation.**
*Xuebo Liu, Derek F. Wong, Yang Liu, Lidia S. Chao, Tong Xiao, Jingbo Zhu.* ACL 2019.  [paper](https://arxiv.org/pdf/1906.03100.pdf)

* **A Tensorized Transformer for Language Modeling.**
*Xindian Ma, Peng Zhang, Shuai Zhang, Nan Duan, Yuexian Hou, Dawei Song, Ming Zhou.* NIPS 2019.  [paper](https://arxiv.org/pdf/1906.09777.pdf)


#### Non/Semi Autoregressive NMT:

* **Non-Autoregressive Neural Machine Translation.**
*Jiatao Gu, James Bradbury, Caiming Xiong, Victor O.K. Li, Richard Socher.* ICLR 2018.  [paper](https://openreview.net/pdf?id=B1l8BtlCb)

* **Semi-Autoregressive Neural Machine Translation.**
*Chunqi Wang, Ji Zhang, Haiqing Chen.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1044)

* **End-to-End Non-Autoregressive Neural Machine Translation with Connectionist Temporal Classification.**
*Jindřich Libovický, Jindřich Helcl.* EMNLP 2018.  [paper](https://www.aclweb.org/anthology/D18-1336)

* **Insertion Transformer: Flexible Sequence Generation via Insertion Operations.**
*Mitchell Stern, William Chan, Jamie Kiros, Jakob Uszkoreit.* ICML 2019.  [paper](https://arxiv.org/pdf/1902.03249.pdf)

* **Constant-Time Machine Translation with Conditional Masked Language Models.**
*Marjan Ghazvininejad, Omer Levy, Yinhan Liu, Luke Zettlemoyer.* Arxiv 2019.  [paper](https://arxiv.org/pdf/1904.09324.pdf)


#### Memory Augmented NMT:

* **Memory-enhanced Decoder for Neural Machine Translation.**
*Mingxuan Wang, Zhengdong Lu, Hang Li, Qun Liu.* EMNLP 2016.  [paper](https://aclweb.org/anthology/D16-1027)

* **Memory-augmented Neural Machine Translation.**
*Yang Feng, Shiyue Zhang, Andi Zhang, Dong Wang, Andrew Abel.* EMNLP 2017.  [paper](https://www.aclweb.org/anthology/D17-1146)

* **Neural Machine Translation with Recurrent Attention Modeling.**
*Zichao Yang, Zhiting Hu, Yuntian Deng, Chris Dyer, Alex Smola.* EACL 2017.  [paper](http://www.aclweb.org/anthology/E17-2061)

* **Learning to Remember Translation History with a Continuous Cache.**
*haopeng Tu, Yang Liu, Shuming Shi, Tong Zhang.* TACL 2018.  [paper](http://aclweb.org/anthology/Q18-1029)

* **Neural Machine Translation with Key-Value Memory-Augmented Attention.**
*Fandong Meng, Zhaopeng Tu, Yong Cheng, Haiyang Wu, Junjie Zhai, Yuekui Yang, Di Wang.* IJCAI 2018.  [paper](https://www.ijcai.org/proceedings/2018/0357.pdf)

* **Encoding Gated Translation Memory into Neural Machine Translation.**
*Qian Cao and Deyi Xiong.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1340)

#### Dropped Pronoun Problem:

* **A Novel Approach to Dropped Pronoun Translation.**
*Longyue Wang, Zhaopeng Tu, Xiaojun Zhang, Hang Li, Andy Way, Qun Liu* NAACL 2016.  [paper](http://www.aclweb.org/anthology/N16-1113)

* **Translating Pro-Drop Languages with Reconstruction Models.**
*Longyue Wang, Zhaopeng Tu, Shuming Shi, Tong Zhang, Yvette Graham, Qun Liu.* AAAI 2018.  [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16187/16026)

* **Learning to Jointly Translate and Predict Dropped Pronouns with a Shared Reconstruction Mechanism.**
*Longyue Wang, Zhaopeng Tu, Andy Way, Qun Liu.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1333)

#### Weight Tying:

* **Using the Output Embedding to Improve Language Models.**
*Ofir Press, Lior Wolf.* EACL 2017.  [paper](http://aclweb.org/anthology/E17-2025)

* **Beyond Weight Tying: Learning Joint Input-Output Embeddings for Neural Machine Translation.**
*Nikolaos Pappas, Lesly Miculicich Werlen, James Henderson.* WMT 2018.  [paper](http://aclweb.org/anthology/W18-6308)

#### Convolutional NMT:

* **Convolutional Sequence to Sequence Learning.**
*Jonas Gehring, Michael Auli, David Grangier, Denis Yarats, Yann N. Dauphin.*  ICML 2017.  [paper](https://arxiv.org/pdf/1705.03122.pdf)

* **Pervasive Attention: 2D Convolutional Neural Networks for Sequence-to-Sequence Prediction.**
*Maha Elbayad, Laurent Besacier, Jakob Verbeek.*  CoNLL 2018.  [paper](https://www.aclweb.org/anthology/K18-1010)

<h2 id="document-level">Discourse and Document-level NMT:</h2>

* **Neural Machine Translation with Extended Context.**
*Jorg Tiedemann and Yves Scherrer.* DiscoMT 2017.  [paper](http://www.aclweb.org/anthology/W17-4811)

* **Does Neural Machine Translation Benefit from Larger Context?.**
*Sebastien Jean, Stanislas Lauly, Orhan Firat, Kyunghyun Cho.* EMNLP 2017.  [paper](https://arxiv.org/pdf/1704.05135.pdf)

* **Exploiting Cross-Sentence Context for Neural Machine Translation.**
*Longyue Wang, Zhaopeng Tu, Andy Way, Qun Liu.* EMNLP 2017.  [paper](http://aclweb.org/anthology/D17-1301)

* **Evaluating Discourse Phenomena in Neural Machine Translation.**
*Rachel Bawden, Rico Sennrich, Alexandra Birch, Barry Haddow.* NAACL 2018.  [paper](http://aclweb.org/anthology/N18-1118)

* **Context-Aware Neural Machine Translation Learns Anaphora Resolution.** 
*Elena Voita, Pavel Serdyukov, Rico Sennrich, Ivan Titov.* ACL 2018.  [paper](http://www.aclweb.org/anthology/P18-1117)

* **When a Good Translation is Wrong in Context: Context-Aware Machine Translation Improves on Deixis, Ellipsis, and Lexical Cohesion.** 
*Elena Voita, Rico Sennrich, Ivan Titov.* ACL 2019.  [paper](https://arxiv.org/pdf/1905.05979.pdf)

* **Exploiting Cross-Sentence Context for Neural Machine Translation.**
*Longyue Wang, Zhaopeng Tu, Andy Way, Qun Liu.* EMNLP 2017.  [paper](http://aclweb.org/anthology/D17-1301)

* **Document Context Neural Machine Translation with Memory Networks.**
*Sameen Maruf, Gholamreza Haffari.* ACL 2018.  [paper](http://aclweb.org/anthology/P18-1118)

* **Improving the Transformer Translation Model with Document-Level Context.**
*Jiacheng Zhang, Huanbo Luan, Maosong Sun, FeiFei Zhai, Jingfang Xu, Min Zhang, Yang Liu.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1049)

* **Document-Level Neural Machine Translation with Hierarchical Attention Networks.**
*Lesly Miculicich, Dhananjay Ram, Nikolaos Pappas, James Henderson.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1325)

* **Selective Attention for Context-aware Neural Machine Translation.**
*Sameen Maruf, André F. T. Martins, Gholamreza Haffari.* NAACL 2019.  [paper](https://arxiv.org/pdf/1903.08788.pdf)

* **Modeling Coherence for Discourse Neural Machine Translation.**
*Hao Xiong, Zhongjun He, Hua Wu, Haifeng Wang.* AAAI 2019.  [paper](https://arxiv.org/pdf/1811.05683.pdf)

* **Modeling Coherence for Neural Machine Translation with Dynamic and Topic Caches.**
*Shaohui Kuang, Deyi Xiong, Weihua Luo, Guodong Zhou.* COLING 2018.  [paper](http://aclweb.org/anthology/C18-1050)

* **Fusing Recency into Neural Machine Translation with an Inter-Sentence Gate Model.**
*Shaohui Kuang, Deyi Xiong.* COLING 2018.  [paper](http://aclweb.org/anthology/C18-1051)

* **A Large-Scale Test Set for the Evaluation of Context-Aware Pronoun Translation in Neural Machine Translation.**
*Mathias Müller, Annette Rios, Elena Voita, Rico Sennrichu.* WMT 2018.  [paper](http://aclweb.org/anthology/W18-6307)

* **Coreference and Coherence in Neural Machine Translation: A Study Using Oracle Experiments.**
*Dario Stojanovski, Alexander Fraser.* WMT 2018.  [paper](http://aclweb.org/anthology/W18-6306)

* **Contextual Neural Model for Translating Bilingual Multi-Speaker Conversations.**
*Sameen Maruf, André F. T. Martins, Gholamreza Haffari.* WMT 2018.  [paper](http://aclweb.org/anthology/W18-6311)

* **Context-Aware Learning for Neural Machine Translation.**
*Sébastien Jean, Kyunghyun Cho.* Arxiv 2019.  [paper](https://arxiv.org/pdf/1903.04715.pdf)


<h2 id="objectivefunction">Objective Function:</h2>

* **Bag-of-Words as Target for Neural Machine Translation.**
*Shuming Ma, Xu Sun, Yizhong Wang, Junyang Lin.*  ACL 2018.  [paper](http://www.aclweb.org/anthology/P18-2053)

* **Differentiable Sampling with Flexible Reference Word Order for Neural Machine Translation.**
*Weijia Xu, Xing Niu, Marine Carpuat.*  NAACL 2019.  [paper](https://arxiv.org/pdf/1904.04079.pdf)

<h2 id="robustness">Robustness:</h2>

* **Robust Neural Machine Translation with Joint Textual and Phonetic Embedding.**
*Hairong Liu, Mingbo Ma, Liang Huang, Hao Xiong, Zhongjun He.*  ACL 2019.  [paper](https://arxiv.org/pdf/1810.06729.pdf)

* **Robust Neural Machine Translation with Doubly Adversarial Inputs.**
*Yong Cheng, Lu Jiang, Wolfgang Machereye.*  ACL 2019.  [paper](https://arxiv.org/pdf/1906.02443.pdf)

* **MTNT: A Testbed for Machine Translation of Noisy Text.**
*Paul Michel, Graham Neubig.* EMNLP 2018.  [paper](https://www.aclweb.org/anthology/D18-1050)

* **Improving Robustness of Machine Translation with Synthetic Noise.**
*Vaibhav Vaibhav, Sumeet Singh, Craig Stewart, Graham Neubig.* NAACL 2019.  [paper](https://www.aclweb.org/anthology/N19-1190)

* **Synthetic and Natural Noise Both Break Neural Machine Translation.**
*Yonatan Belinkov, Yonatan Bisk.* ICLR 2018.  [paper](https://arxiv.org/pdf/1711.02173.pdf)

* **Training on Synthetic Noise Improves Robustness to Natural Noise in Machine Translation.**
*Vladimir Karpukhin, Omer Levy, Jacob Eisenstein, Marjan Ghazvininejad.* Arxiv 2019.  [paper](https://arxiv.org/pdf/1902.01509.pdf)

<h2 id="data">Data Augmentation:</h2>

* **Dynamic Data Selection for Neural Machine Translation.**
*Marlies van der Wees, Arianna Bisazza, Christof Monzy.* EMNLP 2017.  [paper](https://www.aclweb.org/anthology/D17-1147)

* **SwitchOut: an Efficient Data Augmentation Algorithm for Neural Machine Translation.**
*Xinyi Wang, Hieu Pham, Zihang Dai, Graham Neubig.* EMNLP 2018.  [paper](https://aclweb.org/anthology/D18-1100)

* **Code-Switching for Enhancing NMT with Pre-Specified Translation.**
*Kai Song, Yue Zhang, Heng Yu, Weihua Luo, Kun Wang, Min Zhang.* NAACL 2019.  [paper](https://www.aclweb.org/anthology/N19-1044)

* **Soft Contextual Data Augmentation for Neural Machine Translation.**
*Jinhua Zhu, Fei Gao, Lijun Wu, Yingce Xia, Tao Qin, Wengang Zhou, Xueqi Cheng, Tie-Yan Liu.* ACL 2019.  [paper](https://arxiv.org/pdf/1905.10523.pdf)

#### Back-Translation:

* **Improving Neural Machine Translation Models with Monolingual Data.**
*Rico Sennrich, Barry Haddow, Alexandra Birch.* ACL 2016.  [paper](http://www.aclweb.org/anthology/P16-1009)

* **Back-Translation Sampling by Targeting Difficult Words in Neural Machine Translation.**
*Marzieh Fadaee, Christof Monz.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1040)

* **Understanding Back-Translation at Scale.**
*Sergey Edunov, Myle Ott, Michael Auli, David Grangier.* EMNLP 2018.  [paper](https://aclanthology.info/papers/D18-1045/d18-1045)

* **Generalizing Back-Translation in Neural Machine Translation.**
*Miguel Graça, Yunsu Kim, Julian Schamper, Shahram Khadivi, Hermann Ney.* WMT 2019.  [paper](https://arxiv.org/pdf/1906.07286.pdf)

* **Tagged Back-Translation.**
*Isaac Caswell, Ciprian Chelba, David Grangier.* WMT 2019.  [paper](https://arxiv.org/pdf/1906.06442.pdf)

<h2 id="lowsource">Low Source:</h2>

* **Copied Monolingual Data Improves Low-Resource Neural Machine Translation.**
*Anna Currey, Antonio Valerio Miceli Barone, and Kenneth Heafield.* WMT 2017.  [paper](http://www.aclweb.org/anthology/W17-4715)

* **Data Augmentation for Low-Resource Neural Machine Translation.**
*Marzieh Fadaee, Arianna Bisazza, Christof Monz.* ACL 2017.  [paper](https://arxiv.org/pdf/1705.00440.pdf)

* **Rapid Adaptation of Neural Machine Translation to New Languages.**
*Graham Neubig, Junjie Hu.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1103)

* **Generalized Data Augmentation for Low-Resource Translation.**
*Mengzhou Xia, Xiang Kong, Antonios Anastasopoulos, Graham Neubigz.* ACL 2019.  [paper](https://arxiv.org/pdf/1906.03785.pdf)

* **Revisiting Low-Resource Neural Machine Translation: A Case Study.**
*Rico Sennrich, Biao Zhang.* ACL 2019.  [paper](https://arxiv.org/pdf/1905.11901.pdf)

<h2 id="domainadaptation">Domain adaptation:</h2>

* **Sentence Embedding for Neural Machine Translation Domain Adaptation.**
*Rui Wang, Andrew Finch, Masao Utiyama and Eiichiro Sumita.* ACL 2017.  [paper](http://www.aclweb.org/anthology/P17-2089)

* **Adapting Neural Machine Translation with Parallel Synthetic Data.**
*Mara Chinea-R´ıos, Alvaro Peris, Francisco Casacuberta.* WMT 2017.  [paper](https://www.statmt.org/wmt17/pdf/WMT14.pdf)

* **Multi-Domain Neural Machine Translation with Word-Level Domain Context Discrimination.**
*Jiali Zeng, Jinsong Su, Huating Wen, Yang Liu, Jun Xie, Yongjing Yin, Jianqiang Zhao.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1041)

* **Extreme Adaptation for Personalized Neural Machine Translation.**
*Paul Michel, Graham Neubig.* ACL 2018.  [paper](http://aclweb.org/anthology/P18-2050)

* **Learning Hidden Unit Contribution for Adapting Neural Machine Translation Models.**
*David Vilar.* NAACL 2018.  [paper](http://www.aclweb.org/anthology/N18-2080)

* **Improving Domain Adaptation Translation with Domain Invariant and Specific Information.**
*Shuhao Gu, Yang Feng, Qun Liu.* NAACL 2019.  [paper](https://arxiv.org/pdf/1904.03879.pdf)

<h2 id="multilingual">Multi-lingual/source/task NMT:</h2>

* **Multi-Source Neural Translation.**
*Barret Zoph and Kevin Knight.* NAACL 2016.  [paper](http://www.aclweb.org/anthology/N16-1004)

* **Neural System Combination for Machine Translation.**
*Long Zhou, Wenpeng Hu, Jiajun Zhang, Chengqing Zong.* ACL 2017.  [paper](http://aclweb.org/anthology/P17-2060)

* **Attention Strategies for Multi-Source Sequence-to-Sequence Learning.**
*Jindřich Libovický, Jindřich Helcl.* ACL 2017.  [paper](http://aclweb.org/anthology/P17-2031)

* **Doubly-Attentive Decoder for Multi-modal Neural Machine Translation.**
*Jindřich Libovický, Jindřich Helcl.* ACL 2017.  [paper](http://aclweb.org/anthology/P17-1175)

* **Input Combination Strategies for Multi-Source Transformer Decoder.**
*Jindřich Libovický, Jindřich Helcl and David Marecek.* WMT 2018.  [paper](http://www.statmt.org/wmt18/pdf/WMT026.pdf)

* **Multimodal Machine Translation with Embedding Prediction.**
*Tosho Hirasawa, Hayahide Yamagishi, Yukio Matsumura, Mamoru Komachi.* NAACL SRW 2018.  [paper](https://www.aclweb.org/anthology/N19-3012)

* **Multi-Source Syntactic Neural Machine Translation.**
*Anna Currey, Kenneth Heafield.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1327)

* **Multi-Source Neural Machine Translation with Data Augmentation.**
*Yuta Nishimura, Katsuhito Sudoh, Graham Neubig, Satoshi Nakamura.* IWSLT 2018.  [paper](https://arxiv.org/pdf/1810.06826.pdf)

#### Multilingual:

* **Multi-task Sequence to Sequence Learning.**
*Minh-Thang Luong, Quoc V. Le, Ilya Sutskever, Oriol Vinyals, Lukasz Kaiser.* ICLR 2016.  [paper](https://arxiv.org/pdf/151*06114.pdf)

* **Contextual Parameter Generation for Universal Neural Machine Translation.**
*Emmanouil Antonios Platanios, Mrinmaya Sachan, Graham Neubig, Tom Mitchell.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1039)

* **Rapid Adaptation of Neural Machine Translation to New Languages.**
*Graham Neubig, Junjie Hu.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1103)

* **Three Strategies to Improve One-to-Many Multilingual Translation.**
*Yining Wang, Jiajun Zhang, Feifei Zhai, Jingfang Xu and Chengqing Zong.* EMNLP 2018.  [paper](http://aclweb.org/anthology/D18-1326)

* **Parameter Sharing Methods for Multilingual Self-Attentional Translation Models.**
*Devendra Singh Sachan, Graham Neubig.* WMT 2018.  [paper](http://aclweb.org/anthology/W18-6327)

* **Addressing word-order Divergence in Multilingual Neural Machine Translation for extremely Low Resource Languages.**
*Rudra Murthy V, Anoop Kunchukuttan, Pushpak Bhattacharyya.* ACL 2018.  [paper](https://www.aclweb.org/anthology/N19-1387)


<h2 id="externalknowledge">Incorporate External Knowledge:</h2>

* **Inducing Grammars with and for Neural Machine Translation.**
*Ke Tran, Yonatan Bisk.* WNMT 2018.  [paper](http://aclweb.org/anthology/W18-2704)

* **Using Target-side Monolingual Data for Neural Machine Translation through Multi-task Learning.**
*Tobias Domhan and Felix Hieber.* EMNLP 2017.  [paper](http://aclweb.org/anthology/D17-1158)

* **Modeling Source Syntax for Neural Machine Translation.**
*Junhui Li, Deyi Xiong, Zhaopeng Tu, Muhua Zhu, Min Zhang, Guodong Zhou.* ACL 2017.  [paper](http://aclweb.org/anthology/P17-1064)

* **Syntax-Directed Attention for Neural Machine Translation.**
*Kehai Chen, Rui Wang, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao.* AAAI 2018.  [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16060/16008)

* **Syntax-Enhanced Neural Machine Translation with Syntax-Aware Word Representations.**
*Meishan Zhang, Zhenghua Li, Guohong Fu, Min Zhang.*  NAACL 2019.  [paper](https://arxiv.org/pdf/1905.02878.pdf)

* **Addressing Troublesome Words in Neural Machine Translation.**
*Yang Zhao, Jiajun Zhang, Zhongjun He, Chengqing Zong, and Hua Wu.* EMNLP 2018.  [paper](http://www.aclweb.org/anthology/D18-1036)

* **Semantic Neural Machine Translation using AMR.**
*Linfeng Song, Daniel Gildea, Yue Zhang, Zhiguo Wang, Jinsong Su.*  ACL 2019.  [paper](https://arxiv.org/pdf/1902.07282.pdf)

* **Improving Neural Machine Translation with Neural Syntactic Distance.**
*Chunpeng Ma, Akihiro Tamura, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao.*  NAACL 2019.  [paper](https://www.aclweb.org/anthology/N19-1205)

* **Lattice-Based Recurrent Neural Network Encoders for Neural Machine Translation.**
*Jinsong Su, Zhixing Tan, Deyi Xiong, Rongrong Ji, Xiaodong Shi, Yang Liu.*  AAAI 2017.  [paper](https://arxiv.org/pdf/1609.07730.pdf)

* **Lattice-Based Transformer Encoder for Neural Machine Translation.**
*Fengshun Xiao, Jiangtong Li, Hai Zhao, Rui Wang, Kehai Chen.* ACL 2019.  [paper](https://arxiv.org/pdf/1906.01282.pdf)

#### Controling NMT

* **Controlling Politeness in Neural Machine Translation via Side Constraints.**
*Rico Sennrich, Barry Haddow, Alexandra Birch.*  NAACL 17.  [paper](https://www.aclweb.org/anthology/N16-1005)

* **A Study of Style in Machine Translation: Controlling the Formality of Machine Translation Output.**
*Xing Niu, Marianna Martindale, Marine Carpuat.*  EMNLP 17.  [paper](https://www.aclweb.org/anthology/D17-1299)

* **Improved Neural Machine Translation using Side Information.**
*Cong Duy Vu Hoang, Gholamreza Haffari, Trevor Cohn.*  ALTA 18.  [paper](https://www.aclweb.org/anthology/U18-1001)

* **Equalizing Gender Biases in Neural Machine Translation with Word Embeddings Techniques.**
*Joel Escudé Font, Marta R. Costa-jussà.*  ACL WS 2019.  [paper](https://arxiv.org/pdf/1901.03116.pdf)

<h2 id="oov">Open Vocabulary Problem:</h2>

* **Addressing the Rare Word Problem in Neural Machine Translation.**
*Minh-Thang Luong, Ilya Sutskever, Quoc V. Le, Oriol Vinyals, Wojciech Zaremba.* ACL 2015.  [paper](https://www.aclweb.org/anthology/P15-1002)

* **On Using Very Large Target Vocabulary for Neural Machine Translation.**
*Sébastien Jean, Kyunghyun Cho, Roland Memisevic, Yoshua Bengio.* ACL 2015.  [paper](https://www.aclweb.org/anthology/P15-1001)

* **Neural Machine Translation of Rare Words with Subword Units.**
*Rico Sennrich and Barry Haddow and Alexandra Birch.* ACL 2016.  [paper](http://www.aclweb.org/anthology/P16-1162)

* **Subword Regularization: Improving Neural Network Translation Models with Multiple Subword Candidates.**
*Taku Kudo.* ACL 2018.  [paper](http://www.aclweb.org/anthology/P18-1007)

<h2 id="evaluation">Evaluation:</h2>

* **Statistical Significance Tests for Machine Translation Evaluation.**
*Philipp Koehn.* EMNLP 2004.  [paper](http://aclweb.org/anthology/W04-3250)

* **Clause Restructuring for Statistical Machine Translation.**
*Michael Collins, Philipp Koehn, Ivona Kucerova.* ACL 2005.  [paper](http://aclweb.org/anthology/P05-1066)

* **BLEU: a Method for Automatic Evaluation of Machine Translation.**
*Kishore Papineni, Salim Roukos, Todd Ward, Wei-Jing Zhu.* ACL 2002.  [paper](https://www.aclweb.org/anthology/P02-1040.pdf)

* **A Call for Clarity in Reporting BLEU Scores.**
*Matt Post.* WMT 2018.  [paper](http://aclweb.org/anthology/W18-6319)

* **On Evaluation of Adversarial Perturbations for Sequence-to-Sequence Models.**
*Paul Michel, Xian Li, Graham Neubig, Juan Miguel Pino.* NAACL 2019.  [paper](https://arxiv.org/pdf/1903.06620.pdf)

* **Adversarial Evaluation of Multimodal Machine Translation.**
*Desmond Elliott.* EMNLP 2018.  [paper](https://aclweb.org/anthology/D18-1329)


<h2 id="unsupervised">Unsupervised NMT:</h2>

