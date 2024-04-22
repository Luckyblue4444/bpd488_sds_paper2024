This respository holds code files for Bryan Doan's Spring 2024 Certificate in Scientific Computation and Data Sciences Research Paper. 
simple_pca.py script was used to demonstrate simple single value decomposition of made up data about students and measured test scores.

cov2d_simulation.py and pipeline_demo.py are not my original code and was taken from the python package ASPIRE tutorial walkthroughs:
https://nam12.safelinks.protection.outlook.com/?url=https%3A%2F%2Fcomputationalcryoem.github.io%2FASPIRE-Python%2Fauto_tutorials%2Fpipeline_demo.html%23several-views-of-the-projection-images&data=05%7C02%7C%7C0f6dcf1e06bf4221a99d08dc6068ef6c%7C31d7e2a5bdd8414e9e97bea998ebdfe1%7C0%7C0%7C638491251022616962%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C0%7C%7C%7C&sdata=Npn2pq1apBSyzi%2B26J%2FFCpz5UnZCeFQ5IFy3PFMdqJU%3D&reserved=0
https://nam12.safelinks.protection.outlook.com/?url=https%3A%2F%2Fcomputationalcryoem.github.io%2FASPIRE-Python%2Fauto_tutorials%2Ftutorials%2Fcov2d_simulation.html%23sphx-glr-auto-tutorials-tutorials-cov2d-simulation-py&data=05%7C02%7C%7C0f6dcf1e06bf4221a99d08dc6068ef6c%7C31d7e2a5bdd8414e9e97bea998ebdfe1%7C0%7C0%7C638491251022624006%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C0%7C%7C%7C&sdata=IYvuvbnph%2BAlCHJOIpj3s76MXdZxnW%2F0OfdoHlLbtoA%3D&reserved=0

pipeline_demo.py creates simulated clean and noisy data based off downloaded cryogentic electron microscopy images from (https://www.ebi.ac.uk/emdb/) 
while cov2d_simulation.py uses estimations of the 2D covariance matrix to denoise images.
The only changes made to the above code from the tutorial was the cryo-em images used was changed to EMD-8012.
