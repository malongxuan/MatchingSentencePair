# MatchingSentencePair
Theano 0.8.2
python 2.7
keras 1.0

This is the code of model “HMDA”.

Run with “THEANO_FLAGS="device=gpu0,floatX=float32,dnn.conv.algo_bwd_filter=deterministic,dnn.conv.algo_bwd_data=deterministic" python main.py -t trecqa/wikiqa/insqa -m listwise -d 300 -e 5 -l 0.001 -b 5”

The code is based on “Dynamic Clipped Attention”
