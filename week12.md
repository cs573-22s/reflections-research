<<<<<<< Updated upstream
=======
COVID-view: Diagnosis of COVID-19 using Chest CT

The researchers have developed a COVID-19 specific 3D view of the chest CT in order help radiologist get an second level opnion to diagnose and observe other problems in the chest area along with COVID diagnosis.
They provide the following results through their pipeline

    1) Automatic segemntation of lungs: They incorporated Hofmanniger et al. lungs segmentation model that was trained on a lrge variety of dieseased lungs, encompassing different lesions and abnormalities with air pockets, tumors, and effusions, and includes COVID-19 data. The algorithm seemed to work and did not show any deviations from true broundary of lungs even with the outliers.

    2) ocalization of lung abnormalities: The system provides segmentation outlines in 2D views for identifying and examining regions of abnormalities, which helps in drawing radiologists attention to regions that need more attention 


    3) Classification: The pipeline uses multiple instance learning, the goal is to train a model to predict labels of unseen bags. The algorithm uses the training sets contain bags where ecah bag is composed of set of instances. In MIL, only the bag level is known and the instance level label is unknown and it suits for medical imaging becuase here only a patient level or imager level label is known
 
    4) Visual interface:  This interface allows the radiologists to visualize chest CT in both 2D and 3D views that enhances the radiologists workflow by providing them with a contemporary discrement of lesions and their morphology for a better diagnosis

    5) Evaluation: The data of 580 CT scans, out of which 343 positivi ethrough RT PCR and 237 were negative were collected. The model was implemented using pytorch and the performance of the model was evaluated using 5 fold cross validation. For the detetction of accuracy, the ROC curve and AUC curve were plotted with a 95% confidence interval. Th results were (ROC) curve (AUC) are 0.952( 95% confidence interval (CI): 0.938, 0.966) and 0.985 (95% CI: 0.981, 0.989), respectively. The sensitivity and specificity are 0.953 (95% CI: 0.932, 0.974) and 0.949 (95% CI: 0.928, 0.97), respectively

The researchers, I think were successful in developing a model that high accuracy and reliability to diagnose COVID-19 and helps radiologists as second reader. 
    
>>>>>>> Stashed changes
