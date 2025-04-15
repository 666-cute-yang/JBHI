# JBHI
JBHI--Efficient Federated Clustering with Gradient Search Optimization for Medical Edge Networks
Experiment Setup
The basic framework used in this experiment is based on pflib, with some modifications to the original code as per the references in the paper.
--Data: The experiment uses three datasets: PathMNIST, BloodMNIST, and OrganMNIST.
--Experiment Condition: The experiments were conducted under the conditions where the distribution of the dataset's classes was set to 0.1 and 1, with 100 trials.
Command Line for Running the Experiment
The file has already stored datasets under different data distributions, and the experiment can be run using multi-threading with the sh1-1.py file.
python main1.py -data OrganAMNIST_0.1 -m CNN -algo Local -gr 100 -lr 0.001 -ncl 11 -dev cuda -did 0,1
