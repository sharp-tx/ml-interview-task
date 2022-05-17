# ML Interview Task

One of the biggest challenges for us is predicting the risk of an event happening based on certain features. The task is to estimate the risk of death within 5 years on the folowing dataset.

This dataset contains measurements of serum free light chain for 7874 subjects[1].

The dataset has 9 features:
- `age`: age in years
- `sex`: F=female, M=male
- `sample.yr`: the calendar year in which a blood sample was obtained
- `kappa`: serum free light chain, kappa portion
- `lambda`: serum free light chain, lambda portion
- `flc.grp`: the serum free light chain group for the subject, as used in the original analysis
- `creatinine`: serum creatinine
- `mgus`: whether the subject had been diagnosed with monoclonal gammapothy (MGUS)
- `chapter`: for those who died, a grouping of their primary cause of death by chapter headings of the International Code of Diseases ICD-9
- `death`: boolean indicating whether the subject died or the event time is right censored
- `futime`: total length of follow-up or time of death, in days

The endpoint is death, which occurred for 2169 subjects (27.5%).

## Task

We would like you to:
- Create a prototype model estimating the risk of death within 5 years, using python
- Detail the approach you have taken
- Visualise the output of the model using an appropriate format
- Explain model selection and justification as to why this was chosen over other approaches
- Success criteria
- Highlight any current limitations in the model
- Highlight any key findings or insights
- Discuss subsequent next steps

We will not be looking into the details of the paper.

[1] Dispenzieri, A., Katzmann, J., Kyle, R., Larson, D., Therneau, T., Colby, C., Clark, R., Mead, G., Kumar, S., Melton III, LJ. and Rajkumar, SV. Use of monclonal serum immunoglobulin free light chains to predict overall survival in the general population, Mayo Clinic Proceedings 87:512-523. (2012)
