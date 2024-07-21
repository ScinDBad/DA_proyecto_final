# Contact Center Optimization
  
## Description
  Identify inefficient operators based on dropped calls and long wait times for incoming calls, and low number of outgoing calls; so that supervisors can make decisions regarding staff training and management to improve operational efficiency and customer satisfaction.

## Insights

  
![image](https://github.com/user-attachments/assets/9296a9df-9e21-430d-a8f6-e3d4734d61fd)

The efficiency of operators is moderately proportional to their work performance, 
so it can be generalized that An operator can be effective if they increase their overall performance.
For operators to be effective, they should prioritize their tasks in the following order:
- Not missing calls.
- Minimizing customer wait times.
- Calling customers.
  
For operators to increase their performance, they should prioritize their tasks in the following order:

- Minimizing customer wait times.
- Not missing calls.
- Calling customers.<br><br>

![image](https://github.com/user-attachments/assets/eae14260-4de3-4392-83c9-1a748ec3a35d)

Approximately 750 operators (95%) lost 3 incoming calls. Few operators lost more than 1000 calls. 
This shows that the majority of operators comply with losing few incoming calls. 
In this case, 98.8% of operators are effective, as they take less time than the allowed average of 10.55 seconds to answer incoming calls.

Here, the median is a nominally exaggerated threshold, so the mean of 10.55 seconds is a more reasonable benchmark for future periods.<br><br>

![image](https://github.com/user-attachments/assets/39713479-5857-4496-a518-28a378dcea14)

95% of operators take at most 192 seconds to answer incoming calls, and only half of the operators 
manage to answer calls before 31.18 seconds, which is below the allowed average of 59.8 seconds. 
In this task, 24.47% of operators are not effective.

A threshold of 31.17 seconds is a reasonable wait time for answering incoming calls, 
while 59.76 seconds might be too long for the customer to be attended to. 
The median or a value of 30 seconds can be defined as a new threshold.<br><br>

![image](https://github.com/user-attachments/assets/4a7f8251-a3ca-415c-9f85-f3423bde028d)

95% of operators make fewer than 2298 outgoing calls, and only half of the operators make at most 34 calls, 
which is significantly lower than the expected average of 580 calls. 
Based on this parameter, 79.5% of operators are ineffective in this task.

Operators should consistently make calls, and while reaching 580 calls is not unreasonable, 
it would mean only 21.47% of operators succeed. In this case, choosing the median of 34 
calls is more reasonable, but setting a threshold at 200 outgoing calls might be more practical without being too lenient.<br><br>

![image](https://github.com/user-attachments/assets/0e567d96-b37c-4043-b63b-83061fd08951)<br>
![image](https://github.com/user-attachments/assets/947a6ac9-3793-4b21-a33d-01bba04e82e1)

779 operators were effective, meeting all basic tasks according to the thresholds defined 
by the average of each task. 316 operators (29%) were ineffective and need specific 
follow-up based on their deficiencies, detailed as follows:

![image](https://github.com/user-attachments/assets/ed2f9b8e-63aa-44f4-ab18-6e6656de46d0)

Based on the presented dashboard, it is observed that operators made around 44,000 external calls and 5,500 internal calls, each totaling 200 calls. For a more detailed view and filtered data, you can interact with this dashboard at: https://public.tableau.com/app/profile/adrian.vinueza/viz/proyecto_sp14/Dashboard1


## Process
  <img src="https://github.com/ScinDBad/DA_proyecto_final/assets/153782475/abe0622c-7976-4ea1-b6d0-1f0d6d13abd5" alt="Diagrama en blanco8" width="500"><br>


### 🛠️Tools:<br>
Python, Jupyter, Project IDX

<img src="https://github.com/ScinDBad/gamEda/assets/153782475/b44447b0-2286-4c64-889c-1944c1c7e51c" alt="Diagrama en blanco1" width="175"><br>

<a href="https://idx.google.com/import?url=https://github.com/ScinDBad/DA_proyecto_final">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://cdn.idx.dev/btn/open_dark_32@2x.png">
  <source media="(prefers-color-scheme: light)" srcset="https://cdn.idx.dev/btn/open_light_32@2x.png">
  <img height="32" alt="Open in IDX" src="https://cdn.idx.dev/btn/open_purple_32@2x.png">
</picture>
</a>

___
### ⚙️Instructions:
- Create a virtual environment
- __For local work:__ Install `Python 3.11.8`
- __For Cloud work:__ Set/enable the packages `pkgs.python311`, `pkgs.python311Packages.pip` in the .idx/dev.nix file.
- Install `requirements.txt`

_**Note:**
This project was carried out within the Project IDX environment (by Google) based on Nix.
A virtual environment was used to utilize Python version 3.11.8 supported by the environment and other libraries for data analysis.
The requirements.txt file contains detailed dependencies used in the project to function in the IDX environment.
The .idx/dev.nix file contains the package configuration to be used, which are: `pkgs.python311`, `pkgs.python311Packages.pip`._

