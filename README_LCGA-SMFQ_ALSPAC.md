# PREVENTAstudy
This script has been created using Mplus v8. This refers to latent class growth analyses, to detect the trajectories of depression (using the total score of the Short Mood and Feelings Questionnaire), across adolescence and young adulthood (i.e. 6 points: 12.5y, 13.5y, 16y, 18y, 21y, 22y), using the ALSPAC cohort.
ID refers to the Identification of each individual in the study.
DEP13Y = total score SMFQ at 12.5y
DEP14Y = total score SMFQ at 13.5y
DEP16Y = total score SMFQ at 16y
DEP18Y = total score SMFQ at 18y
DEP21Y = total score SMFQ at 21y
DEP22Y = total score SMFQ at 22y
missing=all(999); all missing cases are reported as "999"
CLASSES=c(2); in this example, we were testing the 2-classes model, but this can be easily changed by changing here the number of classes that you want to test. The estandard approach in LCGA is to test all models from 2 to 6 classes, both included.
