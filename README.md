# RAPIDS
This is me exploring RAPIDS AI

Rapids is a open-source framework that uses GPU for data science tasks such as data pre-processing and also model building. It is significantl faster than traditional CPU tasks
## Results and Insights

Our comprehensive comparison between traditional CPU-based data science workflows, using scikit-learn, and GPU-accelerated approaches with RAPIDS AI's cuDF and cuML, highlights significant performance enhancements.

### Performance Overview

The project focuses on the execution times for data preprocessing and model training phases across both technologies. Here's a summary of our findings:


- **Model Training:**
  - cuML training time: ` 52.8 milli seconds`
  - scikit-learn training time: `208 milli seconds`
  - **Insight:** Model training with cuML is about `4 times` faster, demonstrating the efficiency of GPU acceleration for machine learning tasks.

### Detailed Analysis

The analysis reveals that RAPIDS AI significantly reduces the time required for both data preprocessing and model training. This efficiency gain is especially notable in larger datasets and more complex models, where the computational overhead becomes increasingly pronounced.

By leveraging GPU acceleration, data scientists and researchers can achieve faster iterations and more extensive model experimentation, leading to quicker insights and more robust model development.

### Conclusion

Our comparison underscores the transformative potential of RAPIDS AI for data science workflows. The shift from CPU to GPU computing, facilitated by cuDF and cuML, offers a path towards more efficient and scalable data science practices.
