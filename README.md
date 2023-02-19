# DS-Sampling-Assignment

# Comparison of 5 Sampling Techniques for 5 Machine Learning Models

## Sampling Techniques

The following five sampling techniques were used in this project:

1. **Simple Random Sampling:** In a simple random sample, every member of the population has an equal chance of being selected. Your sampling frame should include the whole population.To conduct this type of sampling, you can use tools like random number generators or other techniques that are based entirely on chance.

![m1](https://user-images.githubusercontent.com/75723834/219950512-96c9ccd8-170c-441d-8dd9-3203c502ab83.png)


2. **Stratified Sampling:** Stratified sampling involves dividing the population into subpopulations that may differ in important ways. It allows you draw more precise conclusions by ensuring that every subgroup is properly represented in the sample.

![m2](https://user-images.githubusercontent.com/75723834/219950516-fdbded1e-f8e6-49e2-848d-34984bc81b55.png)


3. **Systematic Sampling:** Systematic sampling is similar to simple random sampling, but it is usually slightly easier to conduct. Every member of the population is listed with a number, but instead of randomly generating numbers, individuals are chosen at regular intervals.

![m3](https://user-images.githubusercontent.com/75723834/219950523-3ed4c17c-016d-42fe-a4ac-6f6609c3f2c9.png)


4. **Cluster Sampling:** Cluster sampling also involves dividing the population into subgroups, but each subgroup should have similar characteristics to the whole sample. Instead of sampling individuals from each subgroup, you randomly select entire subgroups.

![m4](https://user-images.githubusercontent.com/75723834/219950532-853c0fdf-cc18-4471-8bef-f2e4e1dea22a.png)


5. **Convenience Sampling:** A convenience sampling is an easy and inexpensive way to gather initial data, but there is no way to tell if the sample is representative of the population, so it can’t produce generalizable results. Convenience samples are at risk for both sampling bias and selection bias.

 ![m5](https://user-images.githubusercontent.com/75723834/219950547-689dc9a4-bff0-4d1d-874d-b851309cd602.png)



## Comparison Table

The table below shows the accuracies of each sampling technique on five different machine learning models. 

| Sampling Technique | Decision Tree | Gradient Boosting Classifier | Logistic Regression | KNN | Linear Discriminant Analysis |
|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Simple Random Sampling | 0.9778 | 0.9813 | 0.8917 | 0.8915 | 0.8805 |
| Systematic Sampling | 0.9813 | 0.9944 | 0.9213 | 0.9493 | 0.9158 |
| Stratified Sampling | 0.9851 | 0.9963 | 0.9217 | 0.9498 | 0.8791 |
| Cluster Sampling | 0.9868 | **0.9971** | 0.9088 | 0.9691 | 0.8971 |
| Convenience Sampling | 0.9849 | 0.9962 | 0.9322 | 0.9623 | 0.8833 |

The model which gives the best accuracy for all 5 samples is **Decision Tree**.

## Conclusion

Cluster sampling gives best results for this dataset.Hence cluster sampling must be preferred for this dataset.

