# twitter-pos-tagging
Exploration of POS tagging via sequence labeling, via a conditional random field model.
Utilizes the AllenNLP library for simplifying embedding and encoding.


### Usage
To run allennlp training/evaluation with CRF implementation:
allennlp train [JSON training data file path] -s [save point file path] --include-package neural_crf
allennlp evaluate <MODEL_DIR>/model.tar.gz [JSON test data file path] --include-package neural_crf
