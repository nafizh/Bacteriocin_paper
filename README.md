# Bacteriocin paper
This repository contains all the major jupyter notebooks,and files that were produced for the prediction of bacteriocin. Brief
descriptions of the files are:

- Baseline_pipeline.ipynb: This file has the code to generate the baseline performance for predicting bacteriocins in the paper.
- Identifying_gene_blocks_for_putative_bacteriocins.ipynb: The identification of 50kb geneblocks for potential bacteriocins.
- Making_bacteria_wordvectors.ipynb: Generating wordvectors for each 3-gram using Uniprot TrEMBL bacteria database.
- Making_negative_training_set.ipynb: Creating the primary, second, and third negative bacteriocin dataset from Uniprot Swissprot
bacteria database.
- SVM_and_other_models.ipynb: SVM and other model performance with the word2vec representation of amino acid sequences.
- bidirectional_rnn.ipynb: Bidirectional RNN performance with the word2vec representation of amino acid sequences.
- all_curated_context_genes_proper.fa: The 1240 curated context genes using annotation keywords.
- all_lactobacillus_sequences_from_geneblocks: All the sequences from all of the 50kb geneblocks.
- final_NN_model.h5: Weights for the final RNN model used for bacteriocin prediction on the geneblock sequences.
- primary_bacteriocin_training_set: The primary negative bacteriocin set used to train the final model.
- second_bacteriocin_training_set: The second negative bacteriocin set only used to show further performance.
- third_bacteriocin_training_set: The third negative bacteriocin set only used to show further performance.
- word2vec_model_trembl_size_200_gensim: word2vec vectors for each 3-gram in gensim binary format.
- word2vec_model_trembl_size_200.txt: word2vec vectors for each 3-gram in txt format.
