# BuildMyWorld-RSE

## Description -->
Project 1 of the Robotics Software Engineering Nanodegree Program at Udacity. The objective was to build a structure using the Building Editor tool in Gazebo. Additionally, a mobile robot of my choice was to be built and added to this structure. Lastly, the message “Welcome to Manavendra’s World!” was to be shown on the screen as soon as the respective Gazebo file was launched.

## Outcomes -->

- Built a model of my **apartment** in Gazebo
- Built a wheeled **mobile robot** and housed it in my apartment
- Incorporated a **plugin** `welcome.cpp` to print a welcome message once the apartment loaded in Gazebo

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


