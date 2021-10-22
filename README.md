# Extended Kalman Filter Project 
In this project, I will be using  C++ to program a Kalman filter that estimates the state of a moving object with noisy lidar and radar measurements. Passing the project requires obtaining RMSE values that are lower than the tolerance outlined in the project rubric. 


<p align="center">
  <img width="460" height="300" src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/150a730d-42a7-431a-8c50-7f8d487032ce/Screenshot_2021-10-22_164305.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20211022%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20211022T142750Z&X-Amz-Expires=86400&X-Amz-Signature=addda559ec3926786b09efb721a7b9818d7ecbbdbeb89e30066c86143cf0538c&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Screenshot%25202021-10-22%2520164305.png%22">
</p>


# What are we trying to solve? 
Assume you want to measure the position and velocity of an object. You looked at what is available in the market and you have come across two choices either radar or lidar. You started comparing the two, however, each one of them contains a feature that you need in your project. Here, where the Kalman filter comes, it integrates these two sensors for you to get the best possible measurement/prediction. 



<p align="center">
  <img width="460" height="300" src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/e52bf3a2-43e4-4fdf-9c67-4cf8565332bc/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20211022%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20211022T141543Z&X-Amz-Expires=86400&X-Amz-Signature=afe0e8b63a1d85ded6589ccbef21df16711dde4a4e25e2756356da9b35867726&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22">
</p>
