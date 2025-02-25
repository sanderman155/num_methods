# First Homework
----------------
## The first task is my implementation of the Gaus method
### GETTING STARTED
 **to run this program execute this comand**
  ```
  jupyter notebook Gaus.ipynb
  ```
The following five graphs compare the _calculation accuracy_ of my implementation of the Gaus method with the library __numpy.linalg.solve()__ for a matrix of dimensions 100x100, 200x200, 300x300, 400x400, 500x500.
![alt text](Gaus_graphics/100x100.png "Расхождение")

![alt text](Gaus_graphics/200x200.png "Расхождение")

![alt text](Gaus_graphics/300x300.png "Расхождение")

![alt text](Gaus_graphics/400x400.png "Расхождение")

![alt text](Gaus_graphics/500x500.png "Расхождение")

As you can see, the algorithm calculates with an accuracy of ~ __10^-16__ (which is very good).

And this graph shows the dependence of the execution time on the dimension of the matrix. As you can see, the graph is similar to ___n^3___, which corresponds to the _complexity of the algorithm_.

![alt text](Gaus_time_dependes_of_quantity.png "Скорость")

## The second task is my implementation of the Cholesky method
### GETTING STARTED
 **to run this program execute this comand**
  ```
  jupyter notebook Cholesky.ipynb
  ```

The following five graphs compare the _calculation accuracy_ of my implementation of the Gaus method with the library __numpy.linalg.Cholesky()__ for a matrix of dimensions 100x100, 200x200, 300x300, 400x400, 500x500.
![alt text](Cholesky_graphics/040x040.png "Расхождение")

![alt text](Cholesky_graphics/080x080.png "Расхождение")

![alt text](Cholesky_graphics/120x120.png "Расхождение")

![alt text](Cholesky_graphics/160x160.png "Расхождение")

![alt text](Cholesky_graphics/200x200.png "Расхождение")

As you can see, the algorithm calculates with an accuracy of ~ __10^-13__ (which is very good).

And this graph shows the dependence of the execution time on the dimension of the matrix.
![alt text](Cholecky_time_dependes_of_quantity.png "Скорость")
## the third task is my implementation of the sweep method
### GETTING STARTED
 **to run this program execute this comand**
  ```
  jupyter notebook Sweep.ipynb
  ```

The following five graphs compare the _calculation accuracy_ of my implementation of the Gaus method with the library __numpy.linalg.solve()__ for a matrix of dimensions 100x100, 200x200, 300x300, 400x400, 500x500.
![alt text](Sweep_graphics/1000x1000.png "Расхождение")

![alt text](Sweep_graphics/2000x2000.png "Расхождение")

![alt text](Sweep_graphics/3000x3000.png "Расхождение")

![alt text](Sweep_graphics/4000x4000.png "Расхождение")

![alt text](Sweep_graphics/5000x5000.png "Расхождение")

As you can see, the algorithm calculates with an accuracy of ~ __10^-15__ (which is very good).

And this graph shows the dependence of the execution time on the dimension of the matrix.

![alt text](Sweep_time_dependes_of_quantity.png "Скорость")
