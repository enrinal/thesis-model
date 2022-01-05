## Aspect-based Sentiment Analysis

Keras implementation (tensorflow backend) of aspect based sentiment analysis

### Models

- [IAN, IJCAI 2017](https://arxiv.org/pdf/1709.00893.pdf)  
Ma ei al. "Interactive Attention Networks for Aspect-Level Sentiment Classification"

### Pre-processing

1. download glove embedding `glove.42B.300d.zip`, unzip and put it in `raw_data`  
```
wget https://nlp.stanford.edu/data/wordvecs/glove.42B.300d.zip
unzip glove.42B.300d.zip
mv glove.42B.300d.txt ./raw_data
```

2. pre-processing
```
python3 process_raw.py
python3 preprocess.py
```

### Training
```
python3 train.py
```

### Environment
- python==3.6.4
- keras==2.2.4
- nltk==3.2.5
- tensorflow=1.6.0

### Data Analysis

see [data_analysis.md](./data_analysis.md)
