# Cyber-Boolean
import matplotlib.pyplot as plt
import pandas as pd
import numpy as mp
import os

covid = pd.read_csv('/Users/giannajimenez/Downloads/2020VAERSSYMPTOMS (1).csv')
df=pd.read_csv('/Users/giannajimenez/Downloads/2020VAERSSYMPTOMS (1).csv')
covid.head()

df.drop(columns = ['VAERS_ID','SYMPTOMVERSION1','SYMPTOMVERSION2','SYMPTOMVERSION3','SYMPTOMVERSION4','SYMPTOMVERSION5'], inplace=True)
df.head()

fig = plt.pie

sizes = [21138.0, 7607.0, 6673.0, 6301.0,5145,4647,4285,3461,3238,1983,1269,866,507]
labels = 'Pain', 'Erythema', 'Pyrexia', 'Headache','Chills', 'Fatigue','No adverse event','Dizziness', 'Pruritus','Arthralgia','Dyspnoea','Influenza like illness','Muscular weakness'
plt.pie(sizes,labels = labels)

plt.title('2020 COVID Vaccination Symptoms')
plt.axis('equal')
plt.savefig('demo.png', transparent=True)
plt.pie(colors=colors, shadow=True, autopct='%0.2f%%', textprops={'fontsize': 10})

plt.show()

import matplotlib.pyplot as plt
import pandas as pd
import numpy as mp
import os


covid = pd.read_csv('/Users/giannajimenez/Downloads/2021VAERSSYMPTOMS.csv')
df=pd.read_csv('/Users/giannajimenez/Downloads/2021VAERSSYMPTOMS.csv')
covid.head()

df.drop(columns = ['VAERS_ID','SYMPTOMVERSION1','SYMPTOMVERSION2','SYMPTOMVERSION3','SYMPTOMVERSION4','SYMPTOMVERSION5'], inplace=True)
df.head()

fig = plt.pie

sizes = [329142,71493,109886,128532,93059,106949,16081,71045,61088,43554,40940,9856,7179]
labels = 'Pain', 'Erythema', 'Pyrexia', 'Headache','Chills', 'Fatigue','No adverse event','Dizziness', 'Pruritus','Arthralgia','Dyspnoea','Influenza like illness','Muscular weakness'
plt.pie(sizes,labels = labels)

plt.title('2021 COVID Vaccination Symptoms')
plt.axis('equal')
plt.savefig('demo2.png', transparent=True)

plt.pie(colors=colors ,labels=labels, shadow=True,autopct='%0.2f%%', textprops={'fontsize': 10})
explode = explode

plt.show()

import matplotlib.pyplot as plt
import pandas as pd
import numpy as mp
import os

covid = pd.read_csv('/Users/giannajimenez/Downloads/2022VAERSSYMPTOMS.csv')
df=pd.read_csv('/Users/giannajimenez/Downloads/2022VAERSSYMPTOMS.csv')
covid.head()

df.drop(columns = ['VAERS_ID','SYMPTOMVERSION1','SYMPTOMVERSION2','SYMPTOMVERSION3','SYMPTOMVERSION4','SYMPTOMVERSION5'], inplace=True)
df.head()

fig = plt.pie

sizes = [329142,71493,109886,128532,93059,106949,16081,71045,61088,43554,40940,9856,7179]
labels = 'Pain', 'Erythema', 'Pyrexia', 'Headache','Chills', 'Fatigue','No adverse event','Dizziness', 'Pruritus','Arthralgia','Dyspnoea','Influenza like illness','Muscular weakness'
plt.pie(sizes,labels = labels)

plt.title('2022 COVID Vaccination Symptoms')
plt.axis('equal')
plt.savefig('demo3.png', transparent=True)

plt.pie(colors=colors ,labels=labels, shadow=True,autopct='%0.2f%%', textprops={'fontsize': 10})
explode = explode

plt.show()
