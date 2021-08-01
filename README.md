# Coherence_Modelling
official_wikipedia.jsonl and official_cnn.jsonl are the data files for Wikipedia and CNN/Daily news sets, respectively.

For each item, there are 
(1) file_id: the unique id for the file;

(2) ctx: the original file (untouched version);

(3) to_be_replaced: the sentence from the original file, which will be replaced by the "replace_with" sentence;

(4) replace_with: the newly introduced sentence to replace the 'to_be_replaced' sentence in the document;

(5) sen_position: indicating the position of the "to_be_replaced" sentence or the intruder sentence (-1 indicate that the document remain as it is, the coherent document);

(6) train: the flag to indicate whether the document belongs to the train/test set (1 indicates that it is in the train set; otherwise it is in the test set);
