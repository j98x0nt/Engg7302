java c
School of Information Technology  Electrical Engineering
Engg7302 Advanced Computational Techniques in Engineering
Assignment 2 (part B): Linear Algebra (LA) Question
Due date: 23/10/2024 3:00 pm
Where to submit: Submit the assignment report via the Blackboard Turnitin submission system.
Instruction:For this assignment, you must attempt to solve different LA problems. For each question, you are  required to  report  your  results  in  detail.  It  should  include  your  best  solution  and  its corresponding solution  procedures.  If you  are  asked  to  solve those  sub-questions using MATLAB, their MATLAB source code with detailed comments is required.
Marks will be awarded based on how well your submission addresses the above points. This assignment is worth 10% of the total marks for the course.
Question 1 (This question is worth 16% of the total marks for the course)Signal data, represented by b, is collected at 576 sampling points on a spherical surface, as depicted in Figure 1(a). To optimise the uniformity of the signal magnitude on the sphere, specific components are strategically positioned within the 528 meshes on the plane, as shown in Figure 1(b). The optimised signal profile is given by (b'=Ax+b), where b is a vector of the sampled data, x is a vector representing the components placed within the plane’s meshes in Figure 1(b), A is a system matrix that describes the contribution of each mesh element on the plane to the signal points on the sphere.Figure 1: (a) Illustration of the sampling of signal data on a sphere. (b)  a plane with mesh elements 代 写Engg7302 Advanced Computational Techniques in Engineering Assignment 2 (part B): Linear Algebra (LA) QuestionMatlab
代做程序编程语言that optimise the signal magnitude on the sphere.
The optimised signal b' will satisfy the following condition:
|b'- b0|≤∈ bo, where, bo is the mean value of b'.
And ∈ (m) = 0.0008%, m=1, 2, … , M=576.
Additionally, both b and b' are positive vectors.
For each component in vector x, the following conditions are required:
0 ≤x(n)+x0(n) ≤ 0.007, n=1, 2, … , N=528.Where vector x0 has the same dimension as vector x and represents pre-loaded components within the mesh structure depicted in Figure 1(b), indicating that not all meshes are empty before optimisation.
Matrix A, vectors b and x0 are stored in the files A.mat, b.mat and x0.mat respectively. You can access this data in MATLAB using the following commands: load A; load b; load x0.
You are asked to minimise the 1-norm and 2-norm of vector x.
Please prepare the report on the solution details and develop the corresponding MATLAB code.
Note:
To minimise the 1-norm of vector x, use the function linprog ().
To minimise the 2-norm of vector x, use the function fmincon ().
Question 2  (This question is worth 8% of the total marks for the course)
Assessment Type: Application Task Description:
The student needs to prepare a report (at least three pages) on real-world applications that use concepts learned in the linear algebra part.
The presentation should contain the following sections
(1)       introduction;
(2)       theory/methods;
(3)       results and discussion/interpretation;
(4)       conclusion and
(5)       reference.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
