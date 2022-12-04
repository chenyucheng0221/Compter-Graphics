## Spatial Transformation

**Date: 3rd Dec**

#### What is spatial transformation?

  Basically any function that assigns each point a new location.
  
  $$f: R^{n} \rightarrow R^{n}$$
  
#### Applications of linear transformation
  1. position/deform objects in space
  2. move the camera
  3. animate objects over time
  4. project 3D objects onto 2D images
  5. map 2D textures onto 3D objects
  6. projects shadows of 3D objects onto other 3D objects

#### Types of transformation
  1. translation
  2. rotation
  3. scaling
  4. shear

#### New perspective to see transformation

For different transformation, we should focus on invariants preserved during the process.
 
  ![image](../Images/Snipaste_2022-12-04_00-10-29.png)

#### Rotation

*Keeps origin, distance and orientation*

- **2D Rotation**

  Matrix Representation

$$f_{\theta}(x) = \left[\begin{matrix} cos\theta & -sin\theta \\
                                 sin\theta & cos\theta \end{matrix} \right] \left[ \begin{matrix} x_{1} & x_{2} \end{matrix} \right]^{T}$$
  
  In the above matrix representation, we can treat $\left[\begin{matrix} cos\theta sin\theta \end{matrix} \right]^{T}$
