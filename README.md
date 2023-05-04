# Varient-3D-UNets-for-radiotherapy-dose-prediction
We compared four novel knowledge-based planning (KBP) algorithms using deep learning to predict voxel-wise dose for the head and neck radiotherapy treatment plans using similar datasets and assessment metrics. The base of the four KBP models uses the 3D U-Net architecture. They include standard U-Net, attention U-Net, residual U-Net (Res U-Net), and attention Res U-Net.

![image](https://user-images.githubusercontent.com/10604649/236341412-b6dff400-854b-4efe-9f43-dbf1db41180c.png)

Fig. 2. An example of head and neck KBP dose distribution prediction results side-by-side with the ground-truth displayed on different views (axial, coronal, and sagittal) for one patient in the test set. Columns demonstrate the CT image and dose distribution results obtained by 3D U-Net, 3D attention U-Net, 3D Res U-Net, 3D attention Res U-Net, and the ground-truth, respectively. Rows indicate different views and the corresponding dose difference maps.

# Availability of data and materials
The datasets can be found in the OpenKBP - 2020 AAPM Grand Challenge repository at https://competitions.codalab.org/competitions/23428.

# Paper
Please cite this paper: Osman AFI, Tamam NM, Yousif YAM. A comparative study of deep learning-based knowledge-based planning methods for 3D dose distribution prediction of head and neck. J Appl Clin Med Phys. 2023;e14015. https://doi.org/10.1002/acm2.14015
