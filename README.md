# Pôle Projet IA


 ## Contents
- [Organization](#Organization)
- [Installation](#installation)
- [Data collected](#Datacollected)
- [Demo](#demo)

## Organization

In the assets folder, we have 7 subjects, each one referring to a person who has registered their data:

continuous: continuous recordings
posture_data: punctual data of the 7 postures

The following files are included:

- main.ipynb contains the main tasks requested by the client.
- Exploratory.ipynb provides visual tools for the project.
- Test_all_subjects.ipynb utilizes all the collected data.
- Toy_dataset_generation.ipynb and Toy Example - Gaussian Blobs.ipynb are examples provided by the client.

## Installation

Install the required libraries using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

Note: Download and install the TexWorks application for some graphical outputs.
TexWorks can be downloaded from: http://www.tug.org/texworks/


## Data collected

Thanks to the data provided by the client and the data recorded by the previous group, we
initially had data from 7 patients. As described above, the data can be of two types, either spon-
taneous or controlled. For controlled data, the patients had to maintain each of the following 7
postures, one by one, for several tens of seconds :
1. "Correct" posture
2. Leaning forward with feet on the ground
3. Leaning back with right leg crossed
4. Leaning back with left leg crossed
5. Leaning forward with right leg crossed
6. Leaning forward with left leg crossed
7. Leaning back with firm backrest pressure

Moreover we have reused the experimental protocol used by the previous group by recording new
data of ourselves. This time, we maintained the postures for several minutes to collect more data.
This allowed us to have data from 2 additional subjects (3 and 6) to train the atoms


GitHub Copilot
Here’s an improved version of the README.md with a section added for the demo link:

Note: Download and install the TexWorks application for some graphical outputs.
TexWorks can be downloaded from: http://www.tug.org/texworks/

Data collected
Thanks to the data provided by the client and the data recorded by the previous group, we initially had data from 7 patients. As described above, the data can be of two types, either spontaneous or controlled. For controlled data, the patients had to maintain each of the following 7 postures, one by one, for several tens of seconds:

"Correct" posture
Leaning forward with feet on the ground
Leaning back with right leg crossed
Leaning back with left leg crossed
Leaning forward with right leg crossed
Leaning forward with left leg crossed
Leaning back with firm backrest pressure
Moreover, we have reused the experimental protocol used by the previous group by recording new data of ourselves. This time, we maintained the postures for several minutes to collect more data. This allowed us to have data from 2 additional subjects (3 and 6) to train the atoms.

## Demo
A demonstration of the sensing mat in action can be found in the following [video](https://github.com/LucasTramonte/Smart_Chair/blob/main/assets/demo_sensing_mat.mp4):

