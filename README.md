# Bobyard CV Challenge

## Setup

Everything is in the notebook, but just to be sure you can run `make env` to use the conda environment.

## Experiment results

### Best hyperparameters

- Batch size: 2
- Learning rate: 3e-3
- Weight decay: 3e-4

### Settings

epoch: 5
batch_size: [2, 32]
lr: [1e-8, 1e2]
weight_decay: [1e-8, 1e2]

### Output

Trial 1/5
Batch size: 6, Learning rate: 2.1482552614858898e-08, Weight decay: 26.001710262329922
Epoch 1, Train Loss: 4.224683172562543
Epoch 1, Validation Loss: 4.689742088317871
Epoch 2, Train Loss: 4.259113900801715
Epoch 2, Validation Loss: 4.6887688636779785
Epoch 3, Train Loss: 4.247870136709774
Epoch 3, Validation Loss: 4.687761664390564
Epoch 4, Train Loss: 4.28029935500201
Epoch 4, Validation Loss: 4.686305999755859
Epoch 5, Train Loss: 4.258525764240938
Epoch 5, Validation Loss: 4.68584132194519
Test Loss: 4.377034889327155
Trial 2/5
Batch size: 7, Learning rate: 4.1199364857309205e-08, Weight decay: 1.0280964556078314e-06
Epoch 1, Train Loss: 4.22378853389195
Epoch 1, Validation Loss: 4.639591574668884
Epoch 2, Train Loss: 4.2252653666905
Epoch 2, Validation Loss: 4.632250785827637
Epoch 3, Train Loss: 4.2515823500497
Epoch 3, Validation Loss: 4.623861193656921
Epoch 4, Train Loss: 4.256024530955723
Epoch 4, Validation Loss: 4.616187810897827
Epoch 5, Train Loss: 4.236560685294015
Epoch 5, Validation Loss: 4.608231544494629
Test Loss: 4.34876365131802
Trial 3/5
Batch size: 27, Learning rate: 0.10625742902130797, Weight decay: 0.026854952465699074
Epoch 1, Train Loss: 1.1624876222723745e+18
Epoch 1, Validation Loss: 39094.09375
Epoch 2, Train Loss: 257827.94791666666
Epoch 2, Validation Loss: 167.03875732421875
Epoch 3, Train Loss: 2754613986.5873623
Epoch 3, Validation Loss: 3.851520299911499
Epoch 4, Train Loss: 3.8633406162261963
Epoch 4, Validation Loss: 3.820213794708252
Epoch 5, Train Loss: 3.8232998847961426
Epoch 5, Validation Loss: 2.8966413931433165e+18
Test Loss: 2.981234450530042e+18
Trial 4/5
Batch size: 7, Learning rate: 0.000566805649438358, Weight decay: 0.11722365989560707
Epoch 1, Train Loss: 7.448310941803572e+17
Epoch 1, Validation Loss: 6647797759606784.0
Epoch 2, Train Loss: 4083369078798043.5
Epoch 2, Validation Loss: 2999289143885824.0
Epoch 3, Train Loss: 2299850249245257.0
Epoch 3, Validation Loss: 1691831372873728.0
Epoch 4, Train Loss: 1330103935191332.5
Epoch 4, Validation Loss: 942130553946112.0
Epoch 5, Train Loss: 752289164670683.4
Epoch 5, Validation Loss: 514994638684160.0
Test Loss: 517715259060679.1
Trial 5/5
Batch size: 2, Learning rate: 0.005604486929803529, Weight decay: 0.0005532872494429786
Epoch 1, Train Loss: 18199195860144.61
Epoch 1, Validation Loss: 16079.036900111607
Epoch 2, Train Loss: 11077.61205051927
Epoch 2, Validation Loss: 3.6592536653791154
Epoch 3, Train Loss: 5.312864397086349
Epoch 3, Validation Loss: 4.565149102892194
Epoch 4, Train Loss: 3.3048955973456886
Epoch 4, Validation Loss: 3.163413030760629
Epoch 5, Train Loss: 2.5991983366947546
Epoch 5, Validation Loss: 2.8713012082236156
Test Loss: 2.883888496292962
