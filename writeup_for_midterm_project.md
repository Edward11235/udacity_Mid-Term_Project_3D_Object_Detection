# Writeup: Track 3D Object Detection
### Find 10 examples of vehicles with varying degrees of visibility in the point-cloud
In the home folder, there is a picture called point_cloud_with_10_cars_marked.jpg.
In the picture, I marked 10 cars with red color.

### Try to identify vehicle features that appear stable in most of the inspected examples and describe them
If you look closely, for every car in the front, they all have a trunk, which 
is a convex part out of the body of car. Also, above the trunk, there is a 
transparent part, which is the glass of the car. For every car in the back, they all have a bonnet, which 
is a convex part out of the body of car. Also, above the trunk, there is a 
transparent part, which is the windscreen of the car.
For all ten cars, only half of them is shown in the picture since the other half is covered and cannot be detected
by lidar.