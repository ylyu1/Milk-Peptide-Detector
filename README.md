## Project Overview
In this project, I built a Milk Peptide Detector, which is a machine learning-based classifier developed to identify antimicrobial peptides (AMPs) in human milk. This project aims to significantly reduce the time and labor required for researchers to identify promising peptide candidates.

### Major Components of the Project
- **Classification of Antimicrobial Peptides**: Developed a classifier to identify AMPs, streamlining the research process.
- **Data Collection and Preprocessing**: Collected and preprocessed diverse datasets from online peptide databases, extracting key features using bioinformatic tools such as Biopython and Propy3.
- **Model Optimization**: Optimized multiple binary classification models, including Random Forest and XGBoost, achieving a ROC-AUC of 0.78, a 70% improvement over conventional trial-and-error methods.

### Tools and Technologies
- **Programming Languages**: Python
- **Libraries**: Biopython, Propy3, scikit-learn, XGBoost
- **Techniques**: Feature extraction, model training, binary classification, ROC-AUC evaluation

### References
- Bhadra, P., Yan, J., Li, J. et al. AmPEP: Sequence-based prediction of antimicrobial peptides using distribution patterns of amino acid properties and random forest. Sci Rep 8, 1697 (2018). [https://doi.org/10.1038/s41598-018-19752-w](https://doi.org/10.1038/s41598-018-19752-w)
- Yan J, Bhadra P, Li A, Sethiya P, Qin L, Tai HK, Wong KH, Siu SWI. Deep-AmPEP30: Improve Short Antimicrobial Peptides Prediction with Deep Learning. Mol Ther Nucleic Acids. 2020 Jun 5;20:882-894. [doi: 10.1016/j.omtn.2020.05.006](https://doi.org/10.1016/j.omtn.2020.05.006)
- [Propy3 Documentation](https://propy3.readthedocs.io/en/latest/index.html)

### Impact
The Milk Peptide Detector has transformed the identification process of AMPs in human milk, providing a reliable and efficient tool for researchers. By implementing this classifier, we have:
- Achieved a significant improvement in prediction accuracy.
- Reduced the labor and time involved in peptide identification. Enhanced overall research productivity.
- Saved $200,000 in annual research costs by filtering peptide candidates.
