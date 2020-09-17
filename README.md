# Collaborative Filtering for Patient Recommendations

This code offers a generalizable collaborative filtering solution intended to improve the quality of care for patients. Using a JSON file containing data on patients and their histories of medical procedures the solution recommends N number of additional procedures for caregivers to consider.

To run the code call: python get_recs.py {file name} {number of recommendations to return}
> python get_recs.py patient_data.json 5

The code relies on non-negative matrix factorization (NMF) to uncover and leverage latent factors from a patient-procedure matrix. NMF was selected after evaluating a number of other algorithms including KNN, SVD, and one that generates predictions based on (an assumed) normal distribution. Given the nature of the solution, it could be applied in a variety of contexts (e.g. other patients) and extended to new scenarios (e.g. book recommendations) however hyperparameter tuning and re-evaluating the core algorithm would be ideal in the latter.  