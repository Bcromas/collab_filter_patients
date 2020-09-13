Attached you will find "data.json".  This json contains a list with 2000 key:value pairs.  The keys are patient names, and the values contain a list of ICD10-Procedure-Codes that patient has had as of today.  In other words, we have all the procedures a patient has had up to this point in time, and we have that for 2000 patients.  The data is synthetically generated, hence, the ICD10-Procedure-Codes don't really mean anything, they are merely there for illustrative purposes.  There are no tricks placed in this data.

Your overall task is to "improve the quality of care."   There are multiple methods one can take to accomplish such, (Spectral) Clustering, Factorization, Topic Modeling, Dimensionality Reduction, Associative Learning, Autoencoders, etc.  Potential ideas could be identifying:
1) Procedures the patient should be having that they are not?
2) Excess care?
3) Procedure code groupings?

There are no correct answers.

There are 3 guidelines:
A) Python is heavily preferred.
B) Efforts needs to be repeatable, minimize future struggles, and enable further discovery.
C) Whatever solution is devised needs to work during "apply" time.  For example, a ML-based model requires saving after training, and reloading when it's applying.

Hence, try to wrap up your solution such that it can effortlessly work on other data resembling "data.json".
