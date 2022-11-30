# CoronaXNet: Using Convolutional Neural Networks to Automate the Detection of COVID-19 from Chest X-Ray Images
This was an indidivdual research project that I worked on as part of my research internship with the US Army Research Office. 
Attached below is an abstract, paper, and presentation slides that I used for the project. This project came in first palce at the 2021 New York State Science and Engineering Fair in Computational Biology and Informatics. I was also named a Regeneron International Science and Engineering Fair Finalist for the project. 

If the jupyter notebook is not rendering, please refer to the link at the bottom.

# Abstract
With major outbreaks in over 150 countries, the COVID-19 pandemic has had a
devastating effect on public health, daily life, and the global economy. Absent a
vaccine or therapeutic treatment for the novel virus, early diagnosis of infected
persons has become critical to allow for targeted isolation, limiting the probability
of the spread into healthy populations. This study evaluates the ability of deep
learning models to identify the abnormalities in COVID-19 radiographs with the
goal of diagnosing infected patients efficiently and effectively. To do this, transfer
learning was used to train various popular convolutional neural networks on a
collected multiclass dataset that contained chest X-ray images of COVID-19,
pneumonia, and normal patients. After 100 epochs of training, the proposed
hybrid VGG19-LSTM model architecture, CoronaXNet, achieved the highest total
validation accuracy (95.59%) out of all the models and exhibited minimal
overfitting. In contrast, the deeper network architectures tended to be less
accurate as they easily overshot the relatively small dataset. Grad-CAM
heatmaps, which were generated using the gradient information flowing into the
last layer of each head network, showed no irregularities in the evaluation
behavior of the models. Although the achieved performance of CoronaXNet is
promising, further research with a larger sample of COVID-19 radiographs is
required to get a more robust estimate of accuracy rates.

[CoronaXNet.pdf](https://github.com/mcchu3888/CoronaXNet/files/9977150/Michael_Chu___Research_12.pdf)

[Presentation.pdf](https://github.com/mcchu3888/CoronaXNet/files/9977173/Michael.Chu.-.Research.Presentation.12.1.pdf)

https://nbviewer.org/github/mcchu3888/CoronaXNet/blob/main/vgg16-covid19%20%281%29.ipynb
