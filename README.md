# Rank-Your-Summaries-Enhancing-Bengali-Text-Summarization-via-Ranking-based-Approach



## Pretrained Models
We have used bellow pre-trained models for summarization:
- mT5 (mT5 XLSum, mT5 CrossSum, mT5 Shahidul)
- BERT (scibert uncased)

We have used BERT (BanglaBERT) for summary ranking purposes.

## Code
You will find the codes of this project inside the "Code" folder. You need to install specific libraries mentioned in the Notebook to run the code.
- There is a folder named 'Summary Generation with Pre-trained Models' inside the "Code" folder. It contains codes of four summary generator models, all of which generate a summary of Bengali text.
- And a notebook named "Rank_Your_Summaries__Enhancing_Bengali_Text_Summarization_via_Ranking_based_Approach.ipynb" contains codes for:
  - merging datasets
  - ranking summaries
  - generating the final data frame for evaluation
  - and all evaluations.

## Data
You will find both of the datasets used in this project inside the "Data" folder. We have used one Huggingface Dataset and another from Kaggle. For the second one, you need to download it first. 
