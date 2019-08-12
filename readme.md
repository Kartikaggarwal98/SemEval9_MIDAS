# SemEval 2019 Task 9 - SubTask A - Suggestion Mining from Online Reviews and Forums
 
[Competition Link](https://competitions.codalab.org/competitions/19955)

This repository contains the source code of the models submitted by MIDAS team in SemEval 2019 Task 9 - SubTask. It was ranked 10th in the Task with F1 score 0.7011	

The model is described in the paper https://www.aclweb.org/anthology/papers/S/S19/S19-2213/

Citation:
```
@inproceedings{anand2019midas,
  title={MIDAS at SemEval-2019 Task 9: Suggestion Mining from Online Reviews using ULMFit},
  author={Anand, Sarthak and Mahata, Debanjan and Aggarwal, Kartik and Mehnaz, Laiba and Shahid, Simra and Zhang, Haimin and Kumar, Yaman and Shah, Rajiv and Uppal, Karan},
  booktitle={Proceedings of the 13th International Workshop on Semantic Evaluation},
  pages={1213--1217},
  year={2019}
}
```

## TASKS AND LABELS

(A) Sub-task A: 

Under this subtask, participants will perform domain specific suggestion mining, where the test dataset will belong to the same domain as the training and development datasets, i.e. suggestion forum for windows platform developers.


(B) Sub-task B: Automatic categorization of offense types

Under this subtask, participants will perform cross domain suggestion mining, where train/development and test datasets will belong to separate domains. Train and development datasets will remain the same as subtask A, while the test dataset will belong to the domain of hotel reviews

## Evaluation Metrics 

Classification performance of the submissions will be evaluated on the basis of F-1 score for the positive class, i.e. the suggestion class. F1 score will range from 1 to 0.

## CREDITS

Task Organizers

- Sapna Negi (Genesys Telecommunications Laboratory Inc, Galway, Ireland)
- Tobias Daudert (Insight Centre for Data Analytics, National University of Ireland Galway, Galway, Ireland)
- Paul Buitelaar ( Insight Centre for Data Analytics, National University of Ireland Galway, Galway, Ireland)
- Saeedeh Shekarpour (Computer Science Department, University of Dayton, Dayton, Ohio, USA )
