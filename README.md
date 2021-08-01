# Coherence_Modelling
official_wikipedia.jsonl and official_cnn.jsonl are the data files for Wikipedia and CNN/Daily news sets, respectively. Files in the linguistic_prob_data directory are linguistic probe dataset.


For each item, there are 

(1) file_id: the unique id for the file;

(2) ctx: the original file (untouched version);

(3) to_be_replaced: the sentence from the original file, which will be replaced by the "replace_with" sentence;

(4) replace_with: the newly introduced sentence to replace the 'to_be_replaced' sentence in the document;

(5) sen_position: indicating the position of the "to_be_replaced" sentence or the intruder sentence (-1 indicate that the document remain as it is, the coherent document);

(6) train: the flag to indicate whether the document belongs to the train/test set (1 indicates that it is in the train set; otherwise it is in the test set);


If you have any questions please email aili.shen@unimelb.edu.au

# Citing

If you find our paper/code useful, please consider citing:

@article{ailishen2021,<br/>
    &emsp; author = {Shen, Aili and Mistica, Meladel and Salehi, Bahar and Li, Hang and Baldwin, Timothy and Qi, Jianzhong},<br/>
    &emsp; title = "{Evaluating Document Coherence Modeling}",<br/>
    &emsp; journal = {Transactions of the Association for Computational Linguistics},<br/>
    &emsp; volume = {9},<br/>
    &emsp; pages = {621-640},<br/>
    &emsp; year = {2021},<br/>
    &emsp; month = {07},<br/>
    &emsp; abstract = "{While pretrained language models (LMs) have driven impressive gains over morpho-syntactic and semantic tasks, their ability to model discourse and pragmatic phenomena is less clear. As a step towards a better understanding of their discourse modeling capabilities, we propose a sentence intrusion detection task. We examine the performance of a broad range of pretrained LMs on this detection task for English. Lacking a dataset for the task, we introduce INSteD, a novel intruder sentence detection dataset, containing 170,000+ documents constructed from English Wikipedia and CNN news articles. Our experiments show that pretrained LMs perform impressively in in-domain evaluation, but experience a substantial drop in the cross-domain setting, indicating limited generalization capacity. Further results over a novel linguistic probe dataset show that there is substantial room for improvement, especially in the cross- domain setting.}",<br/>
    &emsp; issn = {2307-387X},<br/>
    &emsp; doi = {10.1162/tacl_a_00388},<br/>
    &emsp; url = {https://doi.org/10.1162/tacl\_a\_00388},<br/>
    &emsp; eprint = {https://direct.mit.edu/tacl/article-pdf/doi/10.1162/tacl\_a\_00388/1929699/tacl\_a\_00388.pdf},<br/>
}


