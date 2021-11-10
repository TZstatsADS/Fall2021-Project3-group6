# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Fall 2021

+ Team ##6
+ Team members
	+ Fan, Ruopu 
	+ Nie, Jiayi
	+ Xia, Mingyuan 
	+ Zarate, Rodrigo
	+ Wang, Yalin


+ Project summary: In this project, we created predictive models for image classification using the imperfect dataset provided. Firstly, We consider a baseline model directly on the noisy dataset without any label corrections. RGB histogram features are extracted to fit a logistic regression model. Moreover, we built the two predictive models(model1&model2). For moedel 1 we uesd a more sophisticated model (CNN model) than the baseline, while still treats the noisy labels as clean ones. Fore moedel 2, we used cofident learning. Finally, both models achieve pretty high prediction accuracy(model1 :0.3 ; model2: 0.7).
	
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md))
Ruopu, Rodrigo and Mingyuan studied the model 1. They searched information on the Internet, studied different models, and provided suggestions for modifying and improving the models. Mingyuan and Ruop studied and wrote the codes(CNN&SVM) of model 1, and Ruopu finally modified and improved the codes efficiency. Rodrigo, Jiayi and Mingyuan paid attention to the theoretical study of model 2. They studied the theory and parameter setting of the modelnd, and the final model (condident learning) was confirmed through discussions. Mingyuan was responsible for parameter adjustments and optimization of the model 2 in python. Ruopu was responsible for model evaluation and improvement of the computing efficiency. All team members approve our work presented in this GitHub repository including this contributions statement. 


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
