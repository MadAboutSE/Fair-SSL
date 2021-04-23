# Fair-SSL
This repo is created for ASE 2021 paper - **Fair-SSL: Achieving Fairness using Semi-Supervised Learning**

Ethical bias in machine learning models has become a matter of concern in the software engineering community. Most of the prior software engineering works concentrated on finding ethical bias in models rather than fixing it. After finding bias, the next step is mitigation. Prior researchers mainly tried to use supervised approaches to achieve fairness. However, in the real world, getting data with trustworthy ground truth is challenging and also ground truth can contain human bias. Semi-supervised learning is a domain of machine learning where labeled and unlabeled data both are used to overcome the data labeling challenges. We, in this work, applied five popular semi-supervised techniques as a pre-processor to create fair classification models. Our framework, Fair-SSL,  takes a very small amount of labeled data as input and generates pseudo-labels for the unlabeled data. After that, a classification model is trained on the pseudo-labeled data and generates fairer outcomes without losing much prediction performance. After experimenting on six real world datasets we found out that Fair-SSL performs better or similar than two state-of-the-art bias mitigation algorithms and it requires a much lesser amount of labeled training data. As per our knowledge, this is the first SE work where semi-supervised techniques are used to fight against ethical bias in ML models. 


Dataset Description -

1> Adult Income dataset - http://archive.ics.uci.edu/ml/datasets/Adult

2> COMPAS - https://github.com/propublica/compas-analysis

3> German Credit - https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29

4> Bank Marketing - https://archive.ics.uci.edu/ml/datasets/bank+marketing

5> Default Credit - https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

6> Student - https://archive.ics.uci.edu/ml/datasets/Student+Performance
