# Danish-Similarity-Dataset
The Danish similarity dataset is a gold standard resource for evaluation of Danish word embedding models. The dataset consists of 99 word pairs rated by 38 human judges according to their semantic similarity, i.e. the extend to which the two words are similar in meaning, in a normalized 0-1 range.

Note that this dataset provides a way of measuring similarity rather than relatedness/association.

Description of files included in this material:

(Note: In both of the included files, rows correspond to items (word pairs) and columns to properties of each item.)

*	All_sims_da.csv: Contains the non-normalized mean similarity scores over all judges, along with the non-normalized scores given by each of the 38 judges on the scale 0-6, where 0 is given to the most dissimilar items and 6 to the most similar items.
*	Gold_sims_da.csv: Contains the similarity gold standard for each item, which is the normalized mean similarity score for a given item over all judges. Scores are normalized to a 0-1 range, where 0 denotes the minimum degree of similarity and 1 denotes the maximum degree of similarity.

Author: Nina Schneidermann

Cite: Towards a Gold Standard for Evaluating Danish Word Embeddings
Schneidermann, N., Hvingelby, R. & Pedersen, Bolette Sandford, 2020, Proceedings of the 12th Language Resources and Evaluation Conference, Marseille 2020. pp. 4756-4765  
http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.585.pdf

Contact: Bolette Sandford Pedersen (bspedersen@hum.ku.dk)
