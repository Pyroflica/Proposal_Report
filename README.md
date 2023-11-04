# Proposal_ReportREADME 

Requirements : torch
transformers
datasets
scikit-learn
tqdm
pandas
plotly
kaleido
jupyter
matplotlib

Datasets : As mentioned in the paper that we have chosen, We have requested and succeeded in getting the original datasets used for the paper. 

The hatespeech_text_label_vote_RESTRICTED_100K.csv dataset has been downloaded from: (https://zenodo.org/record/3706866#.Y35QVOzMIZ9)
The test_en.tsv dataset has been downloaded from: 
https://github.com/alisonpr94/SemEval2019-Task5/blob/master/English/TaskA/Dataset/test_en.tsv

Run `evaluate_detexd_roberta.py` to get the published model (grammarly/detexd-roberta-base) results on published dataset (grammarly/detexd-benchmark).

Run `founta_basile_comparison.ipynb` to reproduce results for models comparison from the paper. Note that you need to acquire the datasets because they have separate licences.

Run `country_bias.ipynb` to reproduce country bias analysis.

Run `compare_hatebert.ipynb` to reproduce hatebert models comparison.


As we managed to run the notebooks using the same datasets there were no changes in our executed files from the original ones.
The notebooks that we have executed can be accessed via the below GitHub gist links:
founta_basile_comparison.ipynb : https://gist.github.com/Pyroflica/433c65a6cb9162714da37818ce00673b

country_bias.ipynb : https://gist.github.com/Pyroflica/a4e46f5b711d578f35a461de1f56c3bf

compare_hatebert.ipynb : https://gist.github.com/Pyroflica/afe849af6562edcfd167cef786c8defc
