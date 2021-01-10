---

title: "12NME - Numerical methods" 
excerpt: "Principles of numerical mathematics important for numerical solving of problems related mainly to physics and technology. The course covers methods to solve algebraic equations, nonlinear equations, ordinary differential equations (initial and boundary value problems)."

---

Here you can find auxiliary study materials for undergraduate course <b>12NME - Numerical Methods</b> lectured at the Faculty of Nuclear Sciences and Physical Engineering, Czech Technical University in Prague.

| **academic year:** | 2018/2019 |
| **time:** | Monday, 7:30-9:10 |
| **room:** | T-115 |

### Requirements:

in order to obtain the assessment, there are several formal requirements: 

#### Attendace at tutorials:
- maximum of 3 unjustified absences are allowed throughout the semester  
- please consult the [attendance](https://docs.google.com/spreadsheets/d/1HYbvij7V8GOHL2nAOiQV4H2cIj47VBQIGBNvZAQG7YQ/edit?usp=sharing) list regularly and inform me in case of any error

#### Assessment task:
- you have to solve correctly given task and defend your solution  
- the assessment tasks will be assigned in April, the deadline for submission will be in September (the exact dates will be specified later)  
- first, send me your task solution via e-mail; if your solution is correct, the date of defense will be determined individually upon mutual agreement

Those who obtained the assessment previous year do not have to attend the tutorials again.

Those who attended the tutorials previous year and did not defend the assessment task may get another task to be submitted until the end of March. If the defense of the new assessment task is successfull, they do not have to attend the tutorials again.

### About the study materials:

The study materials currently consist of only the implementation of selected numerical methods and algorithms (without comments). For closer info, you should attend the tutorials. The methods are written in [Python 3](https://www.python.org/), and organized into a collection of Jupyter notebooks. In addition, they rely on several Python packages:
- [numpy](https://numpy.org/) (mainly for data structures)
- [scipy](https://www.scipy.org/) (for several numerical algorithms)
- [matplotlib](https://matplotlib.org/) (for visualization)

Although all these packages can be installed one-by-one, I recommend to obtain them by installing [Anaconda](https://www.anaconda.com/).

#### What is Anaconda and how to install it:

Anaconda is a Python distribution for scientific computing. It includes Jupyter and dozens of the most popular Python packages for scientific computing, including numpy, scipy and matplotlib. 

To install Anaconda, 
1. open [https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual) with your web browser
2. download the suitable Anaconda installer for Windows/MacOS/Linux (you will find them at the bottom of the web page)
3. install Anaconda using all of the defaults for installation except make sure to check that the Anaconda distribution is the default Python

#### How to obtain the notebooks:

All the notebooks are stored in [this](https://github.com/valenpe7/numerical_methods) GitHub repository under the `lectures` directory. You may either download all the notebooks as a [.zip](https://github.com/valenpe7/numerical_methods/archive/master.zip) archive, or use `git`:

1. Clone the repository:  
```$> git clone https://github.com/valenpe7/numerical_methods.git```
2. Pull in new changes:  
``` $> git pull ```

#### How to launch the notebooks:

After you have installed Anaconda on your computer and obtained the notebooks, you are ready to run the notebook server. You can start the notebook server from the command line (Terminal on MacOS/Linux, Anaconda Prompt on Windows) by running:
```
$> jupyter notebook
```
This will print some information about the notebook server in your terminal, including the URL of the web application (by default, `http://localhost:8888`), and open your default web browser to this URL. When Jupyter opens in your browser, you will see the "Notebook Dashboard", which will show a list of the notebooks, files, and subdirectories in the directory where the notebook server was started. Navigate to the `lectures` directory and click on the selected notebook.

Alternatively, if you do not have installed Anaconda, you may launch the notebooks on-line using

* [NBViewer](https://nbviewer.jupyter.org) (non-interactive)
* [Binder](https://mybinder.org) (interactive)

### Tutorials:

<section class="page__content" itemprop="text">

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 00</b> - Introduction to numerical methods
  </summary>
  <p>
    Organization of tutorials, installation and setup of required tools 
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 01</b> - Introduction to Python and Jupyter
  </summary>
  <p>
    Basic concepts and features of Python, numeric and math-related functions and data types, Jupyter environment, numpy, scipy, matplotlib (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/01-introduction.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F01-introduction.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/01-introduction.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 02</b> - Error analysis
  </summary>
  <p>
    Floating point representation of numbers, roundoff error, truncation error, numerical stability and condition number (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/02-error_analysis.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F02-error_analysis.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/02-error_analysis.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 03</b> - Linear algebra
  </summary>
  <p>
    Basic linear algebra operations, direct methods for solving linear equation systems, forward and backward substitution, Gaussian elimination, LU decomposition, Thomas algorithm (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/03-linear_algebra.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F03-linear_algebra.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/03-linear_algebra.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 04</b> - Linear algebra - cont'd
  </summary>
  <p>
    Iterative methods for solving linear equation systems, Jacobi method, Gauss-Seidel method, successive overrelaxation method, power iteration and eigensystems, conjugate gradient method (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/04-linear_algebra_contd.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F04-linear_algebra_contd.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/04-linear_algebra_contd.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 05</b> - Interpolation
  </summary>
  <p>
    Interpolation and extrapolation, piece-wise linear interpolation, Lagrange interpolation and Neville's algorithm, Newton interpolation, Chebyshev approximation and polynomials, cubic spline, least square approximation (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/05-interpolation.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F05-interpolation.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/05-interpolation.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 06</b> - Data sorting 
  </summary>
  <p>
    Various algorithms for data sorting and their comparison, bubble sort, selection sort, insertion sort, shell sort, quicksort, heap sort, benchmarking (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/06-data_sorting.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F06-data_sorting.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/06-data_sorting.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 07</b> - Nonlinear equations 
  </summary>
  <p>
    Root finding and nonlinear set of equations, bisection method, secant method, false position method, Newton-Raphson method (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/07-nonlinear_equations.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F07-nonlinear_equations.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/07-nonlinear_equations.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 08</b> - Numerical optimization
  </summary>
  <p>
    Search for extremes of functions, golden section search, parabolic interpolation search, gradient descent (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/08-optimization.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F08-optimization.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/08-optimization.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 09</b> - Quadrature
  </summary>
  <p>
    Numerical integration of functions, rectangular rule, trapezoidal rule, Simpson's rule, Romberg's method, Gaussian quadrature, Monte-Carlo integration and random number generators (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/09-quadrature.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F09-quadrature.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/09-quadrature.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 10</b> - Initial value problems
  </summary>
  <p>
    Initial value problems of ordinary differential equations, explicit and implicit Euler's method, Runge-Kutta methods, Leap-Frog, Adams-Bashford, Adams-Moulton, predictor-corrector, Bulirsch-Stoer algorithm, stiff equations (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/10-initial_value_problems.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F10-initial_value_problems.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/10-initial_value_problems.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 11</b> - Boundary value problems
  </summary>
  <p>
    Boundary value problems of ordinary differential equations, finite difference method, shooting method (<a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/11-boundary_value_problems.ipynb">nbviever</a>, <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F11-boundary_value_problems.ipynb">binder</a>, <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/11-boundary_value_problems.ipynb">ipynb</a>)
  </p>
</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 12</b> - Individual consultations, evaluation of assessment tasks
  </summary>
  <p>
    Final tutorial, refreshing of selected topics
  </p>
</details>

</section>

The study materials are evolving quickly. Therefore, if you find any mistake, please submit an [issue](https://github.com/valenpe7/numerical_methods/issues) to the GitHub project repository.

### Recommended literature:

[1] W.H. Press, B.P. Flannery, S.A. Teukolsky, V. H. Vetterling, *Numerical Recipes: The art of scientific computing*, Cambridge University Press, Cambridge, 3rd edition 2007 (available at [http://www.numerical.recipes/oldverswitcher.html](http://www.numerical.recipes/oldverswitcher.html)).

[2] A. Ralston, P. Rabinowicz, *A First Course in Numerical Analysis*, McGraw-Hill 1965 (reprinted by Dover Publications, 2001).

[3] R.W. Hamming, *Numerical Methods for Scientists and Engineers*, 2nd edition, Dover Publications 1986.

### Useful links (in Czech):

- [Guidelines to lectures and seminars](http://kfe.fjfi.cvut.cz/~limpouch/numet/NMECvic.pdf)
- [Outline of lecture](http://kfe.fjfi.cvut.cz/~limpouch/numet/sylnum.html)
- [Transparencies of lectures](http://kfe.fjfi.cvut.cz/~limpouch/numet/lecnum.html)
- [References to numerical methods](http://kfe.fjfi.cvut.cz/~limpouch/numet/refnum.html)
- [Further study materials](http://kfe.fjfi.cvut.cz/~vachal/edu/nme/)
