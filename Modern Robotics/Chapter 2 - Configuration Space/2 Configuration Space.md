# 2 Configuration Space
#fundamentals #robotics

The most fundamental question you can ask about a robot is, "Where is it?" The answer to this question is the robot's configuration, which is a specification of the positions of all the points of the robot.

The configuration of a robot is a complete specification of the position of every point of the robot. The minimum number of real-valued coordinates needed to represent the configuration is the number of degrees of freedom (dof) of the robot. 

>The n-dimensional space containing all possible configurations of the robot is called the configuration space (C-space). 

The configuration of a robot is represented by a point in its C-space. The configuration of a rigid body is a specification of the location of all its points. For a rigid body moving in the plane, three independent parameters are needed to specify the configuration. For a rigid body moving in three-dimensional space, six independent parameters are needed to specify the configuration. The configuration of a robot is a specification of the configuration of all its links. The robot's configuration space is the set of all possible robot configurations. The dimension of the C-space is the number of degrees of freedom of a robot.

To visualise the C-space of a body, we can view them as geometrical figures. For example, for a robot with two revolute (hinge) joints, the C-Space for a single joint is a circle (since that joint moves through angle . The second joint will also be a circle, but this circle's centre will originate from the circumference of the circle made by the first joint. To visualise this better, we can make circle #2 perpendicular to circle #1's plane, and we can make a torus out of the arrangement. Thus, every point of the torus will correspond to a unique value of joint #1 and #2, thus leading to unique configurations of the robot. The vice-versa also applies: every unique configuration of the robot will lie on a unique point on the torus.