# Machine Translation Model based on encoder + decoder + attention

## 1. Introduction
These 2 models are based on encoder-decoder structure. And is uesd for French-English translation tasks.

The first model is the "encoder + simple decoder" structure, while the second model added the attention mechanism, and used two generation methods: greedy and beam search.

## 2. Result-Compare
### 2.1 With or without Attention
<p float="center">
  <img src="./IMG/Model%20%20without%20attention.png" width="400" />
  <img src="./IMG/Model%20%20with%20attention.png" width="400" /> 
</p>

### 2.2 Greedy Search or Beam Search
<p float="center">
  <img src="https://github.com/Make0930/Machine-Translation-Model/blob/main/IMG/Greedy-Search.png" width="400" />
  <img src="https://github.com/Make0930/Machine-Translation-Model/blob/main/IMG/Beam_Search.png" width="400" /> 
</p>


## 3. Colcusion
3.1 For long sequences, the attention mechanism can significantly improve model performance

3.2 Beam search can increase the diversity of results
