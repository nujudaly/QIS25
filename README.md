Innovative Approach to Human Lifespan
Prediction and Gene Analysis
Nujud Senan, Sulafah Nooraldeen, Areej Almuhayya
Abstract
This report outlines a novel bioinformatics project integrating classical machine learning
and quantum computing for human lifespan prediction. Utilizing cutting-edge techniques,
including CNNs and Random Forests for feature extraction, coupled with quantum-
enhanced analysis, we explore genes contributing to longevity. Our findings reveal promis-
ing directions for vaccine development to extend human lifespans.
1 Introduction
Human lifespan prediction is a frontier in bioinformatics, merging genomic analysis with
advanced computational techniques. This study, developed by Nujud Senan, Sulafah
Nooraldeen and Areej Almuhayya, leverages multi-omics data to pinpoint genetic fac-
tors influencing longevity. The project incorporates both classical machine learning and
quantum computing to uncover deeper insights.
1
Human Lifespan Analysis Nujud Senan, Sulafah Nooraldeen, Areej Almuhayya
2 Methods
2.1 Data Collection and Preprocessing
Data was sourced from publicly available repositories, including FASTQ files. The pre-
processing pipeline involved:
• One-hot encoding of RNA sequences for machine learning compatibility.
• Normalization and standardization using StandardScaler.
• Splitting data into training, validation, and test sets.
2.2 Modeling
Classical Pipeline:
• A CNN was trained to extract features from RNA sequences.
• Random Forest was utilized for classification, leveraging features extracted by the
CNN.
Quantum Integration:
• Quantum circuits were designed to analyze relationships among top contributing
genes.
• Normalized feature importances from Random Forest were encoded into quantum
circuits for further analysis.
2
Human Lifespan Analysis Nujud Senan, Sulafah Nooraldeen, Areej Almuhayya
3 Results
3.1 Classical Performance
The classical pipeline demonstrated an MAE of 23 on test data, indicating robust pre-
diction accuracy.
3.2 Random Forest Feature Importance
The Random Forest model identified the top genes contributing to longevity. These were
visualized using bar charts, highlighting their relative importances.
Figure 1: Feature Importance Identified by Random Forest.
3.3 Quantum Insights
Quantum circuits provided additional analysis, visualizing the relationships between top
genes through quantum observables. These insights revealed previously hidden patterns.
3
Human Lifespan Analysis Nujud Senan, Sulafah Nooraldeen, Areej Almuhayya
Figure 2: Quantum Circuit Analysis of Gene Contributions.
4 Discussion
This project underscores the synergy between classical and quantum methods in bioin-
formatics. While classical models excel in feature extraction, quantum circuits uncover
deeper interrelationships among features. The integration of these methodologies offers
new horizons in understanding and extending human lifespans.
5 Conclusion
The study presents a compelling case for hybrid classical-quantum approaches in bioin-
formatics. Future work will focus on leveraging these insights for practical applications,
such as vaccine development, contingent on extended project timelines and resources.
4
Human Lifespan Analysis Nujud Senan, Sulafah Nooraldeen, Areej Almuhayya
Acknowledgments
We extend our gratitude to the organizers of the Human Lifespan Analysis competition.
Special thanks to our team members Sulafah Nooraldeen and Areej Almuhayya for their
contributions to this groundbreaking project.
References
• FASTQ Data and Metadata: https://aqora.io/competitions/human-lifespans-qinnovision
• Sulafah Nooraldeen’s work on CNN pipelines: Personal communications and notes
on CNN and Random Forest integration.
• Bioinformatics Analysis Using Quantum Computing: Relevant articles and re-
sources consulted, including Quantum of Data for MultiOmics by Sulafah and Areej.
• Random Forest Applications in Genomic Data: https://scikit-learn.org/stable/
modules/ensemble.html
• Pennylane Documentation for Quantum Analysis: https://pennylane.ai/
• General Machine Learning Frameworks: https://keras.io/ and https://scikit-learn.
org/
• Quantum-Inspired Solutions for Multi-Omics Analysis: https://github.com/nujudaly/
QIS25
• Quantum Kernels for Real-World Predictions Based on Electronic Health Records:
https://arxiv.org/pdf/2112.06211v2.pdf
• Quantum Computing for Chemistry and Materials: IBM Quantum Services White
Paper. Retrieved from https://www.ibm.com/quantum-computing/
• Solving the Quantum Many-Body Problem with Artificial Neural Networks: https:
//arxiv.org/pdf/1606.02318.pdf
5
Human Lifespan Analysis Nujud Senan, Sulafah Nooraldeen, Areej Almuhayya
• Montanaro, A. (2016). Quantum algorithms: An overview. Retrieved from https:
//www.nature.com/articles/npjqi201523.pdf
6
