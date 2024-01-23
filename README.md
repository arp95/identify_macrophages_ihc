# AI-Based Assessment of CD163-Positive Macrophages is Prognostic in HPV-Associated Oropharyngeal Squamous Cell Carcinoma Patients

---


## Abstract
####Background
Prior research has shown the prognostic significance of spatial characteristics derived from tumor-infiltrating lymphocytes in HPV-associated oropharyngeal squamous cell carcinoma (OPSCC). While macrophages (tumor-associated or TAMs) are a critical part of anti-tumoral immunity, they are difficult to identify on H&E slides, and their quantitative and spatial attributes have yet to be studied through image analysis. This study introduces the development and validation of two artificial intelligence (AI) based TAM classifiers using CD163 immunostains and H&E slides for prognosis in HPV-associated OPSCC patients.

####Design
H&E-stained slides from tissue microarray (TMA) slides of OPSCC patients were gathered from two institutions (Vanderbilt University for modeling (N=102), Emory for validation (N=50)). We digitally scanned the slides and immunostained them for CD163 (Novocastra; monoclonal; clone 10D6) on a Leica Bond III immunostainer. We then digitally scanned these slides and co-registered them. For the first classifier, we quantified TAM density by calculating the ratio of TAMs to the number of nuclei present in the TMA punches. To identify TAMs, we leveraged the IHC-stained TMA cores to recognize their characteristic brown staining. For the second classifier, we derived spatial characteristics through the creation of cell cluster graphs of the CD163-positive TAMs. These spatial attributes were employed as features for the development of a Cox regression model (CRM+LASSO), which was trained on the modeling cohort. The CRM+LASSO model identified 23 features for predicting the risk of disease in both cohorts. For these two prognostic classifiers, the mean risk score determined from the modeling cohort was used to stratify patients in each of the cohorts into low and high-risk categories.

####Results
High TAM density was found to be associated with poorer disease free survival for the modeling cohort (HR= 3.28, 95% CI= 1.1-9.32, p= 0.02) and for the validation cohort (HR= 7.04, 95% CI=1.1-22.5, p= 0.03) (Figure 1). Similarly, spatial TAM features were also found to be associated with poorer disease free survival in both cohorts (modeling, HR= 2.73, 95% CI=1.1-8.9, p= 0.04 and validation, HR= 8.5, 95% CI= 1.3-56, p= 0.02) (Figure 2).

####Conclusion
This pilot study shows the prognostic value of CD163 TAM density and spatial attributes of TAMs. Additional independent multi-site and prospective validation of these AI derived TAM features, specifically in whole slides images, is warranted.


## Authors
Arpit Aggarwal, German Corredor, and Anant Madabhushi<br>


## Manuscript files
Please find the required manuscript documents over here (abstract/uscap_abstract.pdf)<br>


## Packages Required
Python, R, and Matlab were used for this study.<br>
The packages required for running this code are PyTorch, Numpy, Openslide, PIL, OpenCV, Pandas, Sksurv, Sklearn, and Matplotlib.<br>