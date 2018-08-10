# text-similarity
nlp for short text similarity calculation


================description==================

CNN model for Q&A(Question and Answering), tensorflow code implementation
计算输入问句与标准问句之间的相似度
支持两种负采样方式
支持多种embedding方式


================dataset================

实验用的是清华大学的新闻分类数据集，实验效果来看
rand负采样的效果会差一些

=================run=====================

训练集和测试集的格式：标签\t问句

数据集demo在：knn-classification/knn-classification/data/

进行分词处理：python insurance_qa_data_helpers.py

训练：
python train.py --model_verion=xxx

model_verion:模型版本号

