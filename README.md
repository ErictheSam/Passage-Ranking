# Passage-Ranking
  
## Introduction
This is the final project in artificial neural network.
We use bert and GAT to train a passage ranking model on MS Marco dataset.
  
## Architecture
We incorporated BERT, a potent model in providing context-based representation of words, as well as GAT, a novel GNN model, to obtain augmented entity embedding. We also add a local model for exact word match in order to enhance the model's ability confronting rare words.
<center>
  
<img src="/fig1.png">  
Figure1. General Model

<img src="/fig2.png">  
Figure2. Distributed Model

</center>
  
See *Final Report.pdf* for detailed description of our architecture.  

## Result
Unfortunately, due to the limitation in time and facility, the final result haven't yet been acquired.

## Work division
Yingzhuo Qian: proposed model；chose dataset; preprocessesd MS Marco data and completed entity
recognition; implemented data loader for model; implemented KNRM and integrated all 3 models;
composed train and eval scripts and conducted experiments; collaborated in writing project proposal,
milestone report and final report.
Yibo Shen: implemented local model and GAT; preprocessed OpenKE entity embeddings into graph
structure; resized entity graph for the need of cutting memory expenses; collaborated in writing
project proposal, milestone report and final report.
