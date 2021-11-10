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
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

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
