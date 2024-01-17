## Dataset

I used data from [INSPIRE dataset, version 1.0](https://physionet.org/content/inspire/1.0/), on [PhysioNet](https://physionet.org/).

Place files from INSPIRE 1.0 into the csv directory in order to knit.

INSPIRE 1.1 was released shortly after starting this project and is the most recent version as of submission.  The changes made from version 1.0 to 1.1 were to 5th percentile categories for better anonimization.  A side effect of doing this was to make it impossible to detect impossible values; I chose to exclude patients who had values of height and weight that cannot occur.  For example, heights and weights that were set as -1 or otherwise physically impossible (likely representing different units than metric) in version 1.0 were set to 146 cm and 43kg, respectively, in version 1.1.

