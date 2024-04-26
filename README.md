# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-

### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.

![image](https://github.com/srishvanths/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/161055755/6c19ff15-681b-4a26-a86d-686b4dbf57ed)


### Figure -01 difference between P-P , joint and linear interpolation 


### Program : 


![image](https://github.com/srishvanths/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/161055755/a7122aa3-3610-499a-9a05-b11db47f6c87)








### Robot movements 

![image](https://github.com/srishvanths/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/161055755/0ad19def-c3ef-44d3-b726-a4e5efa79404)

![Screenshot 2024-04-26 224625](https://github.com/srishvanths/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/161055755/31efb00c-d1ad-4bee-8b24-a40ffa161032)



### Results:

Thus ,linear and joint interpolation of industrial manipulator and program is executed.
