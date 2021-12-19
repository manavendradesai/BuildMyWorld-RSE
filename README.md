# BuildMyWorld-RSE
Project 1 of the Robotics Software Engineering Nanodegree Program at Udacity. 

## Outcomes -->

- Built a model of my **apartment** in Gazebo
- Built a wheeled **mobile robot** and housed it in my apartment
- Incorporated a **plugin** `welcome.cpp` to print a welcome message once the apartment loads in Gazebo

## Directory structure -->

    ├── model                          # Model files 
    │   ├── APT916                     # Build files for an apartment
    │   │   ├── Floorplan.jpeg 
    │   │   ├── model.config
    │   │   ├── model.sdf
    │   ├── ServeronWheels             # Build files for a mobile robot     
    │   │   ├── model.config
    │   │   ├── model.sdf
    ├── script                         # Gazebo World plugin C++ script     
    │   ├── welcome.cpp
    ├── world                          # Gazebo main World containing models 
    │   ├── myApartment
    ├── CMakeLists.txt                 # Link libraries 
    └── media                          # Screenshots of the mobile robot and the apartment in Gazebo


