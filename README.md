# Implement wind sensing with the antennal aristae for wind-guided odor navigation

## Important notification
Due to the OpenCv encoding, videos created for this project that are displayed with an arrow can not be open using all video players, we do not expect base Windows video player to work, try using VLC or other software such as MediaPlayer.

## Aim of the project
The project aims to simulate the behavior of a fly walking upwind in NeuroMechFly. First, a laminar flow was implemented which was thought to be complexified thanks to objects (walls), to create complex plumes. 

## Architecture
Here is how our project is structured

      ├── Bibliography References
      │     ├── Cobar_Wind_Neuro2.pdf
      │     ├── Cobar_Wind_Neuro3.pdf
      ├── Graphs
      │     ├── Aristae_Position
      │     │      ├── Filtered
      │     │      │     ├── Filtered Aristae Position over time Wind flow = [0 ; 0].png
      │     │      │     ├── ... 
      │     │      ├── Raw
      │     │      │     ├── Aristae Position over time Wind flow = [0 ; 0].png
      │     │      │     ├── ...
      │     ├── Fly position_orientation in arena
      │     │     ├── Fly orientation over time Wind flow = [0 ; 0].png
      │     │     ├── ... 
      ├── Test_Notebook
      │     ├── test_add_arrow.ipynb
      │     ├── ... 
      ├── Videos
      │     ├── Fly_wind_orientation
      │     │     ├── With Arrow
      │     │     │     ├── Arrow Video Wind flow = [0 ; 0].mp4
      │     │     │     ├── ...
      │     │     ├── Without Arrow
      │     │     │     ├── Video Wind flow = [0 ; 0].mp4
      │     │     │     ├── ...
      │     └── Obstacles
      │           ├── obstacle_back.mp4
      │           ├── ...
      ├── position_force_DoFs.ipynb
      ├── notebook.ipynb
      ├── Obstacles.ipynb
      ├── README.md     

## Precision on the main notebooks
- **notebook.ipynb** is the main notebook. It contains the main code for the project (wind sensing, turning behavior) and the code to create some relevant graphs and videos to visualize the behavior.
- **obstacles.ipynb** implements obstacles, in order to try to emulate complex plume. In particular, a wall has been simulated to try to block the wind.
- **position_force_DoFs.ipynb** offers the code to compare the force and position sensors signals. It also proposes some code to compare the signals coming from the pitch, roll and yaw DoF's position sensors. Individual DoF stiffness and damping coefficients tuning is also possible through this notebook.

*Please note that in the sensing code we used the "pitch" DoF and not the "yaw" DoF to turn as said in the report !*

# Authors
Killian Raude, Aline Brunner, Emilie Marcou
