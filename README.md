# phys-gmm-python

Notes for Alpha Edition: Support 3D and 2D dataset and option 'full'.
The skeletons have been implemented, later I will add more details in plotted figure, which will be really cool

### Image Gallary

![image](https://user-images.githubusercontent.com/97799818/190874177-67d995b9-b105-47f6-83b0-045c5b0d54f8.png)
<p align="center">
  **L-shape**
</>

![image](https://user-images.githubusercontent.com/97799818/190874280-3fdd430d-9e65-4756-96c7-9afc9697cbeb.png)
<p align="center">
**A-shape**
</>

![image](https://user-images.githubusercontent.com/97799818/190873962-0e82256d-5057-44bb-b33a-b9f18519bfb7.png)
<p align="center">
**S-shape**
</>

![90badeaf0e12caf784f65b6acd6cc2e](https://user-images.githubusercontent.com/97799818/190874080-d6599bec-161c-4075-955a-b799bb9d1062.jpg)
<p align="center">  
**multi-behavior**
</>


Notes for first Edition: Only implement for datasets of 2D and option 'full'.
                         Most code follow the style like Matlab, use class to mimic the struct
                         Z_C means which table the member sits, Z_C[0] = 1 means the first data point sits at table 1
                         C means which datapoint current datapoint sit with, C[0] = 1 means first data point (access by index 0) sits with itself
                         if you want to access table member, likelihood, the index should be minus 1, table_Logliks[0] stores the likelihood of table 1
Dependencies:
- Scipy: https://scipy.org/install/
- Gmr: https://github.com/AlexanderFabisch/gmr
