# Occumancy Grid Mapping Algorithm

for robotic sw engineering course

```cpp
double inverseSensorModel(double x, double y, double theta, double xi, double yi, double sensorData[])
```


Summary of notations for the sonar rangefinder inverse sensor model

mi​: Map at instant i or current cell that is being processed

xi,yix_{i},y_{i}xi​,yi​: Center of mass of the current cell mi

r: Range of the center of mass computed with respect to robot pose and center of mass

k: The sonar rangefinder cone that best aligns with the cell being considered computed with respect to the robot pose (x,y,θ\thetaθ), center of mass (xi,yi), and sensor angle.

β\betaβ: Opening angle of the conical region formed out of the measurement beams.

α\alphaα: Width of obstacles which is almost equal to the size of a cell. Please not that alpha is not the width of the conical region as the video mention but instead it's the width of a cell. 