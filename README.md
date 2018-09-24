# Hashtag2Vec
Hashtag2Vec: Learning Hashtag Representation with Relational Hierarchical Embedding Model

/**
 * This project is developed by the Intelligent Information Processing Lab, Nankai University, Tianjin, China. (http://dm.nankai.edu.cn/)
 * It follows the GPLv3 license. Feel free to use it for non-commercial purpose and please cite our paper:
 * @inproceedings{Hashtag2Vec,
 *   author    = {Jie Liu and Zhicheng He and Yalou Huang},
 *   title     = {Hashtag2Vec: Learning Hashtag Representation with Relational Hierarchical Embedding Model},
 *   booktitle = {Proceedings of the Twenty-Seventh International Joint Conference on Artificial Intelligence, {IJCAI} 2018, July 13-19, 2018, Stockholm, Sweden.},
 *   pages     = {3456--3462},
 *   year      = {2018},
 *   doi       = {10.24963/ijcai.2018/480},
 *   }
 * Contact: jliu@nankai.edu.cn, hezhicheng@mail.nankai.edu.cn
 */

 To run the Hashtag2Vec model, use the codes in the cn.edu.nk.iiplab.hzc.hashtag2vec package.
 Hashtag2Vector.java : the Hashtag2Vec model with a runnable synthetic example in the main function;
 Hashtag2Vector_agg.java : the Hashtag2Vec_agg model with a runnable synthetic example in the main function;
 Logger.java : a tool class to save the running logs;
 Performance.java: the evaluation metrics for the learned embeddings.

 For further project developments, use the tool classes in the cn.edu.nk.iiplab.hzc.basic package.
 cn.edu.nk.iiplab.hzc.basic.MF : some matrix operation functions implemented in a multi-thread way;
 cn.edu.nk.iiplab.hzc.basic.thread : thread classes for cn.edu.nk.iiplab.hzc.basic.MF;
 cn.edu.nk.iiplab.hzc.basic.matrix : dense and sparse matrices;
 cn.edu.nk.iiplab.hzc.basic.struct : some basic data structures;
 cn.edu.nk.iiplab.hzc.basic.util : some tool functions.
