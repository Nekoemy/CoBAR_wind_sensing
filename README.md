# Implement wind sensing with the antennal aristae for wind-guided odor navigation

# Importante notification
Videos created for this project can not be open using VLC. Other videos viewer software need to be used as MediaPlayer.

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
      ├── FindBias.ipynb
      ├── force_vs_torque.ipynb
      ├── notebook.ipynb
      ├── Obstacles.ipynb
      ├── README.md
      └──  WindArrowFinal.ipynb        

# Authors
Killian Raude, Aline Brunner, Emilie Marcou
