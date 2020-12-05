# Parkinson's Disease Prediction
#### As Portfolio Bulding Exercise for Misk-DSI
Pakinson's disease ia a neurodegenerative disorder of centeral nervious system that causes partial or full loss of motor reflexes, behaviour, speech, mental processing. Symptoms start gradually, sometimes starting with a barely noticeable tremor in just one hand.

Stusies concerned with Parkinson's disease focus on symptoms like poor balance, slowness in movement or stiffness of some body parts especially voice problems.

This dataset is composed of a range of biomedical voice measurements from 42 people with early-stage Parkinson's disease recruited to a six-month trial of a telemonitoring device for remote symptom progression monitoring. The recordings were automatically captured in the patient's homes.

**The main aim of the data is to predict Unified Parkinson's Disease Rating Scale (UPDRS) from the 16 voice measures.**

## Data Set Information:

This dataset is composed of a range of biomedical voice measurements from 42 people with early-stage Parkinson's disease recruited to a six-month trial of a telemonitoring device for remote symptom progression monitoring. The recordings were automatically captured in the patient's homes.

Columns in the table contain subject number, subject age, subject gender, time interval from baseline recruitment date, motor UPDRS, total UPDRS, and 16 biomedical voice measures. Each row corresponds to one of 5,875 voice recording from these individuals. The main aim of the data is to predict the motor and total UPDRS scores ('motor_UPDRS' and 'total_UPDRS') from the 16 voice measures.
This data set obtained from [UCI Machine Learning Repository]('http://archive.ics.uci.edu/ml/datasets/Parkinsons+Telemonitoring')


Description of the variables

* **Subject** : Integer that uniquely identifies each subject
* **Age** : Subject age
* **sex** : Subject gender '0' - male, '1' - female
* **test_time** : Time since recruitment into the trial. The integer part is the number of days since recruitment.
* **motor_UPDRS** : Clinician's motor UPDRS score, linearly interpolated
* **total_UPDRS** :Clinician's total UPDRS score, linearly interpolated
* **Jitter(%),Jitter(Abs),Jitter** :RAP,Jitter:PPQ5,Jitter:DDP - Several measures of variation in fundamental frequency
* **Shimmer, Shimmer (dB), Shimmer. APQ3, Shimmer. APQ5, Shimmer. APQ11, Shimmer. DDA** :Several measures of variation in amplitude (Amplitude parameters) NHR, HNR: Two measures of ratio of noise to tonal components in the voice
* **RPDE** : A nonlinear dynamical complexity measure
* **DFA** :Signal fractal scaling exponent
* **PPE** : A nonlinear measure of fundamental frequency variation
