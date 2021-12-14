# drift detector

#### Introduction
The source code of comparison baselines (in section 4.1) and our proposed schemes.

#### Requirements
0. Python3.7.9
1. Keras == 2.3.1
2. numpy == 1.19.1
3. scikit-learn == 0.20.4
4. scipy == 1.6.2
5. tensorflow == 1.15.3

#### Usage
step1. Unzip the zip file using the password.(i.e., unzip -P password final_detector.zip)

Step2. Set the DETECTOR_BASE environment variable to the directory where the source code is located. For example, in Windows, we can use the following commands:

Step2-1. set DETECTOR_BASE=D:\gitcodes\final_detector\

Step2-2. d:

Step2-2. cd %DETECTOR_BASE%\CVAE_concept_drift\

Step2-3. python main_process.py

Step2-4. The data set can be specified by modifying the value in common_tools_pack\config.py. In addition, the mapping between Directory and schemes are shown in map.xlsx.

#### Remark
***The params used in diffderent datasets are shown in the common_tools_pack\config.py***. If you have any questions, please feel free to ask zhanglei0511@iie.ac.cn.
