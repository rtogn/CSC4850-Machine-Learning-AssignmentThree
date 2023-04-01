# CSC4850-Machine-Learning-AssignmentThree
CSC4850-Machine-Learning-AssignmentThree

Git hub repository for Assigment Three covering SVMs and model metrics.

### Contents:
-[Dataset](#dataset)  
-[Results](#results)  
-[Packages Used](#packages-used)  

## Dataset
This assignment uses Chess dataset from Kaggle: [https://www.kaggle.com/datasets/datasnaek/chess]  
From this only the rating difference b/w white and black and the turns are considered, and white_wins is used as the label.


## Results
#### Fold 1 Metrics  
![image](https://user-images.githubusercontent.com/60898339/229257904-eeb0766c-21d1-4c94-b64e-41235e695e23.png)
#### Fold 1 Graphs  
![index1png](https://user-images.githubusercontent.com/60898339/229306077-072f75a8-fc2f-4e5f-aa6e-3f54eb24033e.png)
![index2png](https://user-images.githubusercontent.com/60898339/229306078-78c7f566-86d6-446a-9485-02b615264dfd.png)
![index3png](https://user-images.githubusercontent.com/60898339/229306079-31eb9052-7964-4193-8a42-4bd847b6090d.png)
#### Fold 2 Metrics  
![image](https://user-images.githubusercontent.com/60898339/229258787-cb5b6308-e104-4ad3-abbb-f5668c306b4b.png)
#### Fold 2 Graphs  
![index1png](https://user-images.githubusercontent.com/60898339/229306028-0578d5b4-8142-4891-a507-3b9d9cc84c24.png)
![index2png](https://user-images.githubusercontent.com/60898339/229306030-e6b2362b-d989-4ec9-9175-5dfa8e55dfa0.png)
![index3png](https://user-images.githubusercontent.com/60898339/229306036-dd40abdf-0ab0-4011-8e6e-6664b87eb8c1.png)

#### Fold 3 Metrics  
![image](https://user-images.githubusercontent.com/60898339/229257890-3d1eb022-59f6-4084-942b-9f220bfdbbdc.png)
#### Fold 3 Graphs  
![index1png](https://user-images.githubusercontent.com/60898339/229306106-5094b45f-90ad-4ba2-80e1-6001cf6d6c6f.png)
![index2png](https://user-images.githubusercontent.com/60898339/229306108-0231f4bd-83ff-43a7-90b2-324b31321907.png)
![index3png](https://user-images.githubusercontent.com/60898339/229306112-845579a7-c226-4106-92e9-06662e09cce9.png)

#### Metrics for top model choices among all folds
![image](https://user-images.githubusercontent.com/60898339/229257962-65d9c937-0248-4391-b2fa-db66f10d87c4.png)

#### 3D Graphs Attemtped
I don't beleive these to be correct, but I was able to get some output from the grad question without breaking.  
It seems to involve translating graph calls from some unknown library into matplot lib, which I attempted without knowing all the translations.
![image](https://user-images.githubusercontent.com/60898339/229261554-f535822d-066e-4717-888b-ddf6e04b02ca.png)

## Packages Used
-[Numpy](https://numpy.org/) For array splitting and composition  
-[Pandas](https://pandas.pydata.org/) For creating data frames  
-[Sklearn](https://scikit-learn.org/stable/index.html) For learning models and performance metrics  
-[Matplotlib](https://matplotlib.org/) For all graphs and plots  
