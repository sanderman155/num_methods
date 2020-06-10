# Second Homework
----------------
## the first task is my implementation of the Jacobi method
### GETTING STARTED
 **to run this program execute this comand**
  ```
  jupyter notebook Jacobi.ipynb
  ```

The following five graphs compare the _calculation accuracy_ of my implementation of the Jacobi method with the library __numpy.linalg.solve()__ for a matrix of dimensions 100x100, 150x150, 200x200, 250x250.
![alt text](Jacobi_graphics/100x100.png "Расхождение")

![alt text](Jacobi_graphics/150x150.png "Расхождение")

![alt text](Jacobi_graphics/200x200.png "Расхождение")

![alt text](Jacobi_graphics/250x250.png "Расхождение")

As you can see, the algorithm calculates with an accuracy of ~ __10^-7__ (which is very good).

And this graph shows the dependence of the execution time on the dimension of the matrix.
![alt text](Jacobi_time_dependes_of_quantity.png "Скорость")

## the second task is my implementation of the Zeidel method
### GETTING STARTED
 **to run this program execute this comand**
  ```
  jupyter notebook Zeidel.ipynb
  ```

The following five graphs compare the _calculation accuracy_ of my implementation of the Zeidel method with the library __numpy.linalg.solve()__ for a matrix of dimensions 100x100, 200x200, 300x300, 400x400.
![alt text](Zeidel_graphics/100x100.png "Расхождение")

![alt text](Zeidel_graphics/200x200.png "Расхождение")

![alt text](Zeidel_graphics/300x300.png "Расхождение")

![alt text](Zeidel_graphics/400x400.png "Расхождение")

As you can see, the algorithm calculates with an accuracy of ~ __10^-6__ (which is very good).

And this graph shows the dependence of the execution time on the dimension of the matrix.
![alt text](Zeidel_time_dependes_of_quantity.png "Скорость")
