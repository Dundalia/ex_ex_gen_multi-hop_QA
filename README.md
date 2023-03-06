# ex_ex_gen_multi-hop_QA


In this study, we present a pipeline for an
explainable, extractive-generative multi-hop
OpenQA model trained on the HotPotQA
dataset. Our model features a Retriever Reader architecture, which consists of an
Interaction-based Retriever and Extractor and
a Generative module. We show that our model
outperforms the baseline model of the dataset.
Results show that the Retriever and Extractor submodules perform better on comparison question types rather than bridge question
types, while the opposite is true for the Generator submodule. Performance decreases for
the Retriever with increasing reasoning difficulty, but not for the Extractor and Generator.
Additionally, fine-tuning on the SQuAD v2
dataset was found to enhance multi-hop reasoning ability in the Generator module.
