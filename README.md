# dl-reference
## (conditional) (W)GAN
* [tf training stackoverflow](https://stackoverflow.com/questions/35298326/freeze-some-variables-scopes-in-tensorflow-stop-gradient-vs-passing-variables)
* [document with tf code](https://bobondemon.github.io/2017/03/17/WGAN-Part-2/)
* [sample code](https://github.com/igul222/improved_wgan_training/blob/master/gan_toy.py)
* [stargan](https://arxiv.org/pdf/1711.09020.pdf#page9)
* [cramer gan](https://arxiv.org/pdf/1705.10743.pdf)
* [nvidia gan](https://arxiv.org/pdf/1710.10196.pdf)
* [EFFICIENT GAN-BASED ANOMALY DETECTION](https://arxiv.org/pdf/1802.06222.pdf)
* [ADVERSARIAL FEATURE LEARNING](https://arxiv.org/pdf/1605.09782.pdf)

## tensorflow
* [variable scope](http://www.jianshu.com/p/ab0d38725f88)
* [import images in tf.train.batch](https://stackoverflow.com/questions/37340129/tensorflow-training-on-my-own-image)
* [graphs for training/testing dataset](https://medium.com/@ywchen88/tensorflow-dataset-api-graph-30807178cfa0)
* [freeze partial variables](https://stackoverflow.com/questions/35298326/freeze-some-variables-scopes-in-tensorflow-stop-gradient-vs-passing-variables)
* [ema, exponential moving average](http://ruishu.io/2017/11/22/ema/)
* [name_scope vs variable_scope](https://stackoverflow.com/a/37534656)
* [saved model](http://stackabuse.com/tensorflow-save-and-restore-models/)
* [use training/validation dataset in the training phase](https://stackoverflow.com/questions/47356764/how-to-use-tensorflow-dataset-api-with-training-and-validation-sets)
* Frozen graph with variables:
```
python -m tensorflow.python.tools.freeze_graph \
--input_checkpoint ./model.ckpt \
--input_graph ./nasnet_inf_graph.pb \
--input_binary True \
--output_graph ./frozen_graph.pb
```

## augmentation
* [imaug](https://github.com/aleju/imgaug)
## word2vec
* [structured data document](https://towardsdatascience.com/structured-deep-learning-b8ca4138b848)
* [lda doc](https://towardsdatascience.com/lda2vec-word-embeddings-in-topic-models-4ee3fc4b2843)
## capsulenet
* [youtube intro](https://m.youtube.com/watch?utm_content=buffer4e1ee&v=pPN8d0E3900&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
* [doc intro](https://towardsdatascience.com/demystifying-matrix-capsules-with-em-routing-part-1-overview-2126133a8457)
# dl learning resource
* [goodfellow youtube](https://m.youtube.com/playlist?list=PLkISDyMVw2Htm42P0eTVEKyz7scxZ4V-O)
* [many](https://unsupervisedmethods.com/my-curated-list-of-ai-and-machine-learning-resources-from-around-the-web-9a97823b8524)
# deep reinforcement learning
* [atari paper](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)
# utility
* [tsne](https://buzzrobot.com/using-t-sne-to-visualise-how-your-deep-model-thinks-4ba6da0c63a0)
## pedestrian detection
* [standford](https://web.stanford.edu/class/cs231a/prev_projects_2016/pedestrian-detection-tracking.pdf)
* [【论文笔记】In Defense of the Triplet Loss for Person Re-Identification](http://blog.csdn.net/qq_21190081/article/details/78417215)

## [attention, memory](https://towardsdatascience.com/memory-attention-sequences-37456d271992)

## others
* [best 2017](https://www.reddit.com/r/MachineLearning/comments/7nrzhn/d_results_from_best_of_machine_learning_2017/)
* [alpha zero and keras](https://medium.com/applied-data-science/how-to-build-your-own-alphazero-ai-using-python-and-keras-7f664945c188)
