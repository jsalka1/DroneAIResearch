# DroneAIResearch

Task: Determine if CARLA or Microsoft AirSim could be useful simulators for teaching AI at Universities.

Carla: 

    Opinion:
        - I feel like this simulator could only be used by students if Universities could provide access to higher end
        workstations. However, if this can be provided I think this is the stronger of the two programs with better
        resources online. 
           
    Pros: 
        - More realistic environments can be created with less knowledge of Unreal Engine by running provided scripts to
            change the scene
        - Gives tutorials on how to create your own Vehicle such as a drone
        - Better documentation as of now
        - More diverse array of sensors with the option to make your own
    
    Cons: 
        - Recommended GPU is an Nvidia RTX 2070. Most students won't have access to this without using University workstations
        - Requires Visual Studio 2017 which means you can't use some features on AirSim
        - Can't access data from sensors live. Have to save it to an image and then view it from there
        
    Sensors:
        - Collision, Depth camera, GNSS sensor, IMU sensor, Lane invasion detector, LIDAR sensor, Obstacle detector
        Radar sensor, RGB camera, RSS sensor, Semantic LIDAR sensor, Semantic segmentation camera, DVS camera
    
    Teaching Tools: 
        - Pictures of sensor readings
        
AirSim

    Opinion:
        - I think this simulator is much more suited for student work. The simple "blocks" enviroment that is provided is lightweight
         and makes launching and testing scripts much quicker. This is more ideal for teaching and learning. There are also more teaching
         tools available such as recording the visual and sensors of the drone. 
    
    Pros:
        - Provides less intensive environments for easier and quicker testing
        - Can easily download different maps for more complex scenarios. https://youtu.be/1oY8Qu5maQQ
     
    Cons:
        - Not many cameras or sensors to mess with
        - Less documentation and resources online
        
    Sensors:
        - Camera, Barometer, Imu, Gps, Magnetometer, Distance Sensor, Lidar
    
    Teaching Tools:
        - Picures of sensor readinga
        - Recording the drone's camera and sensor views. Could be used for assignments and easily uploaded to canvas
        - Collision counter for drone. This can be used to grade scripts made by students
