# Deus Ex Machina: Power, Perception, and Prejudice

### Authors: Bernardo Salgado, Daniel Dias, Lucas Santiago, Miguel Lopes, Rafael Conceição  
**Date:** December 2024  
<br>
<br>

## **Table of Contents**
1. [Introduction](#introduction)
2. [Motivation and Goals](#motivation-and-goals)
3. [Dataset](#dataset)
4. [How to Use the Repository](#how-to-use-the-repository)
<br>

## **Introduction**

This project investigates the societal implications of Artificial Intelligence (AI) in real-world applications, focusing on bias and fairness challenges. Through the lens of NYC’s high school admission algorithms, we explore how algorithmic decisions perpetuate racial and economic segregation. Using the **Adult Census Income Dataset**, we performed experiments to identify bias in machine learning models, applied mitigation techniques, and evaluated the trade-offs between fairness and accuracy.
<br>
<br>


## **Motivation and Goals**

1. **Understand the societal impact** of AI-driven systems through real-world case studies.  
2. **Identify key issues** such as bias, fairness, and transparency in algorithmic decision-making.  
3. **Experiment with bias mitigation techniques** to evaluate their effectiveness and limitations.  
4. **Provide actionable insights** for building fairer AI systems while maintaining performance.
<br>


## **Dataset**

The project uses the **Adult Census Income Dataset**, available at:  
[UCI Machine Learning Repository - Adult Dataset](https://www.kaggle.com/datasets/uciml/adult-census-income)  

This dataset predicts whether a person earns more than $50k annually. It includes sensitive attributes such as **race**, **sex**, and **native country**, making it an ideal candidate for our fairness studies.
<br>
<br>


## **How to Use the Repository**

### **1. Clone the Repository**
```bash
git clone https://github.com/v2denny/AIbias.git
cd AIbias
```

### **2. Install Dependencies**
Install required Python libraries:
```bash
pip install -r requirements.txt
```

### **3. Run the Notebooks**
Launch the Jupyter Notebooks and explore the full workflow.
1. **Approach 1:** Run the files on the `Approach1` folder and follow the provided readme instructuons.

<br>
<br>


## **References**

- [The Markup - NYC’s School Algorithms Cement Segregation](https://themarkup.org/machine-learning/2021/05/26/nycs-school-algorithms-cement-segregation-this-data-shows-how)
- [Algorithmic Fairness in Education](https://arxiv.org/abs/2110.00530)
- [Fairlearn Documentation](https://fairlearn.org/)
- [Aequitas Documentation](https://github.com/dssg/aequitas)
