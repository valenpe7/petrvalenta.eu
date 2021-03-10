---

title: "12NME1 - Numerical methods"
excerpt: "Principles of numerical mathematics important for numerical solving of problems related mainly to physics and technology are demonstrated using Python programming language. The course covers methods to solve algebraic equations, nonlinear equations, ordinary differential equations (initial and boundary value problems), methods for interpolation and extrapolation, numerical optimization, and data sorting."

---

Here you can find auxiliary study materials for undergraduate course <b>12NME1 - Numerical methods</b> lectured at the [Faculty of Nuclear Sciences and Physical Engineering](https://www.fjfi.cvut.cz/cz/), [Czech Technical University in Prague](https://www.cvut.cz/).

| **academic year:** | 2020/2021 |
| **time:** | Monday, 7:30 - 9:10 |
| **room:** | T-105 |

**Warning:** Due to the COVID-19 pandemic, the tutorials will be held at the scheduled time remotely using Microsoft Teams ([Team-B202-NME1-Valenta](https://teams.microsoft.com/l/channel/19%3a1004cbffd51143eeb1d526f4066b4d37%40thread.tacv2/General?groupId=1793b8cb-591b-4a71-965e-b01e74a19aae&tenantId=f345c406-5268-43b0-b19f-5862fa6833f8)). If the situation changes, you will be informed.
{: .notice--warning}

### Requirements:

in order to obtain the assessment, there are several formal requirements: 

#### Attendace at tutorials:
- ~~maximum of 3 unjustified absences are allowed throughout the semester~~
- ~~please consult the [attendance](https://teams.microsoft.com/l/file/ED4AE881-3282-490E-A280-63094336D17D?tenantId=f345c406-5268-43b0-b19f-5862fa6833f8&fileType=xlsx&objectUrl=https%3A%2F%2Fcampuscvut.sharepoint.com%2Fsites%2FTeam-B202-12NME1-Valenta%2FSdilene%20dokumenty%2FGeneral%2Fattendance_list.xlsx&baseUrl=https%3A%2F%2Fcampuscvut.sharepoint.com%2Fsites%2FTeam-B202-12NME1-Valenta&serviceName=teams&threadId=19:1004cbffd51143eeb1d526f4066b4d37@thread.tacv2&groupId=1793b8cb-591b-4a71-965e-b01e74a19aae) list regularly and inform me in case of any error~~

#### Assessment task:
- ~~you have to solve correctly given task and defend your solution~~
- ~~the assessment tasks will be assigned in April, the deadline for submission will be in September (the exact dates will be specified later)~~  
- ~~first, send me your task solution via e-mail; if your solution is correct, the date of defense will be determined individually upon mutual agreement~~

Those who obtained the assessment previous year do not have to attend the tutorials again.

Those who attended the tutorials previous year and did not defend the assessment task may get another task to be submitted until the end of March. If the defense of the new assessment task is successfull, they do not have to attend the tutorials again.

**Warning:** Since it is not possible to properly check the attendance in the remote mode, the requirements above are no longer valid. Instead, you will be given a short task at the end of each tutorial. To obtain the assessment, it is neccessary to solve correctly and submit on time at least 6 out of 11 tasks throughout the semester. Please consult the [evaluation](https://teams.microsoft.com/l/file/ED4AE881-3282-490E-A280-63094336D17D?tenantId=f345c406-5268-43b0-b19f-5862fa6833f8&fileType=xlsx&objectUrl=https%3A%2F%2Fcampuscvut.sharepoint.com%2Fsites%2FTeam-B202-12NME1-Valenta%2FSdilene%20dokumenty%2FGeneral%2Fattendance_list.xlsx&baseUrl=https%3A%2F%2Fcampuscvut.sharepoint.com%2Fsites%2FTeam-B202-12NME1-Valenta&serviceName=teams&threadId=19:1004cbffd51143eeb1d526f4066b4d37@thread.tacv2&groupId=1793b8cb-591b-4a71-965e-b01e74a19aae) list regularly and inform me in case of any error.
{: .notice--warning}

### About the study materials:

The study materials currently consist of only the implementation of selected numerical methods and algorithms (without comments). For closer info, you should attend the tutorials. The methods are written in [Python 3](https://www.python.org/), and organized into a collection of [Jupyter](https://www.jupyter.org) notebooks. In addition, they rely on several Python packages:
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
<strong>Tutorial 00</strong> - Introduction to numerical methods
</summary>
<p markdown="1">
Organization of tutorials, installation and setup of required tools
</p>
</details>

<details class="page__content" itemprop="text">
<summary>
<strong>Tutorial 01</strong> - Introduction to Python and Jupyter
</summary>
<p markdown="1">
Basic concepts and features of Python, numeric and math-related functions and data types, Jupyter environment, numpy, scipy, matplotlib modules.  
Download the [assignment](https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_01.ipynb) and submit your soulution in the .ipynb format [here](https://form.jotform.com/210404523662042) (<span style="color:red">deadline: 28/02/2021 23:59 CET</span>).  
Materials from lecture: [nbviewer](https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/01-introduction.ipynb), [binder](https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F01-introduction.ipynb), [ipynb](https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/01-introduction.ipynb)
</p>
</details>

<details class="page__content" itemprop="text">
<summary>
<strong>Tutorial 02</strong> - Error analysis
</summary>
<p markdown="1">
Floating point representation of numbers, roundoff error, truncation error, numerical stability and condition number.   
Download the [assignment](https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_02.ipynb) and submit your soulution in the .ipynb format [here](https://form.jotform.com/210404436620342) (<span style="color:red">deadline: 07/03/2021 23:59 CET</span>).  
Materials from lecture: [nbviewer](https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/02-error_analysis.ipynb), [binder](https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F02-error_analysis.ipynb), [ipynb](https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/02-error_analysis.ipynb)
</p>
</details>

<details class="page__content" itemprop="text">
<summary>
<strong>Tutorial 03</strong> - Linear algebra
</summary>
<p markdown="1">
Basic linear algebra operations, direct methods for solving linear equation systems, forward and backward substitution, Gaussian elimination, LU decomposition, Thomas algorithm.  
Download the [assignment](https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_03.ipynb) and submit your soulution in the .ipynb format [here](https://form.jotform.com/210405082358348) (<span style="color:red">deadline: 14/03/2021 23:59 CET</span>).  
Materials from lecture: [nbviewer](https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/03-linear_algebra.ipynb), [binder](https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F03-linear_algebra.ipynb), [ipynb](https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/03-linear_algebra.ipynb)
</p>
</details>

<details class="page__content" itemprop="text">
<summary>
<strong>Tutorial 04</strong> - Linear algebra (cont'd)
</summary>
<p markdown="1">
Iterative methods for solving linear equation systems, Jacobi method, Gauss-Seidel method, successive overrelaxation method, power iteration and eigensystems, conjugate gradient method.  
Download the [assignment](https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_04.ipynb) and submit your soulution in the .ipynb format [here](https://form.jotform.com/210405178142345) (<span style="color:red">deadline: 21/03/2021 23:59 CET</span>).  
Materials from lecture: [nbviewer](https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/04-linear_algebra_contd.ipynb), [binder](https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F04-linear_algebra_contd.ipynb), [ipynb](https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/04-linear_algebra_contd.ipynb)
</p>
</details>

<details class="page__content" itemprop="text">
<summary>
<strong>Tutorial 05</strong> - Interpolation
</summary>
<p markdown="1">
Piece-wise linear interpolation, Lagrange interpolation and Neville's algorithm, Chebyshev polynomials and approximation, linear and quadratic least squares interpolation.  
Download the [assignment](https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_05.ipynb) and submit your soulution in the .ipynb format [here](https://form.jotform.com/210405129320339) (<span style="color:red">deadline: 28/03/2021 23:59 CET</span>).  
Materials from lecture: [nbviewer](https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/05-interpolation.ipynb), [binder](https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F05-interpolation.ipynb), [ipynb](https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/05-interpolation.ipynb)
</p>
</details>


<!--

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 06</b> - Data sorting 
  </summary>
  <p>
    Various algorithms for data sorting and their comparison, bubble sort, selection sort, insertion sort, shell sort, quicksort, heap sort, benchmarking.
  </p>

  <p> Download the 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_06.ipynb" download>asignment</a> 
    and submit your soulution in the .ipynb format 
    <a href="https://">here</a> 
    (deadline: 11/04/2021 23:59 CET).
  </p>

  <p> Materials from lecture:
    <a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/06-data_sorting.ipynb">nbviewer</a>, 
    <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F06-data_sorting.ipynb">binder</a>, 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/06-data_sorting.ipynb" download>ipynb</a>
  </p>

</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 07</b> - Nonlinear equations 
  </summary>
  <p>
    Root finding and nonlinear set of equations, bisection method, secant method, false position method, Newton-Raphson method.
  </p>

  <p> Download the 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_07.ipynb" download>asignment</a> 
    and submit your soulution in the .ipynb format 
    <a href="https://">here</a> 
    (deadline: 18/04/2021 23:59 CET).
  </p>

  <p> Materials from lecture:  
    <a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/07-nonlinear_equations.ipynb">nbviewer</a>, 
    <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F07-nonlinear_equations.ipynb">binder</a>, 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/07-nonlinear_equations.ipynb" download>ipynb</a>
  </p>

</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 08</b> - Numerical optimization
  </summary>
  <p>
    Search for extremes of functions, golden section search, parabolic interpolation search, gradient descent.
  </p>

  <p> Download the 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_08.ipynb" download>asignment</a> 
    and submit your soulution in the .ipynb format 
    <a href="https://">here</a> 
    (deadline: 25/04/2021 23:59 CET).
  </p>

  <p> Materials from lecture:  
    <a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/08-optimization.ipynb">nbviewer</a>, 
    <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F08-optimization.ipynb">binder</a>, 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/08-optimization.ipynb" download>ipynb</a>
  </p>

</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 09</b> - Quadrature
  </summary>
  <p>
    Numerical integration of functions, rectangular rule, trapezoidal rule, Simpson's rule, Romberg's method, Gaussian quadrature, Monte-Carlo integration and random number generators.
  </p>

  <p> Download the 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_09.ipynb" download>asignment</a> 
    and submit your soulution in the .ipynb format 
    <a href="https://">here</a> 
    (deadline: 02/05/2021 23:59 CET).
  </p>

  <p> Materials from lecture:  
    <a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/09-quadrature.ipynb">nbviewer</a>, 
    <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F09-quadrature.ipynb">binder</a>, 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/09-quadrature.ipynb" download>ipynb</a>
  </p>

</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 10</b> - Initial value problems
  </summary>
  <p>
    Initial value problems of ordinary differential equations, explicit and implicit Euler's method, Runge-Kutta methods, Leap-Frog, Adams-Bashford, Adams-Moulton, predictor-corrector, Bulirsch-Stoer algorithm, stiff equations.
  </p>

  <p> Download the 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_10.ipynb" download>asignment</a> 
    and submit your soulution in the .ipynb format 
    <a href="https://">here</a> 
    (deadline: 09/05/2021 23:59 CET).
  </p>

  <p> Materials from lecture:  
    <a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/10-initial_value_problems.ipynb">nbviewer</a>, 
    <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F10-initial_value_problems.ipynb">binder</a>, 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/10-initial_value_problems.ipynb" download>ipynb</a>
  </p>

</details>

<details class="page__content" itemprop="text">
  <summary>
    <b>Tutorial 11</b> - Boundary value problems
  </summary>
  <p>
    Boundary value problems of ordinary differential equations, finite difference method, shooting method.
  </p>

  <p> Download the 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/tasks/task_11.ipynb" download>asignment</a> 
    and submit your soulution in the .ipynb format 
    <a href="https://">here</a> 
    (deadline: 16/05/2021 23:59 CET).
  </p>

  <p> Materials from lecture: 
    <a href="https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/lectures/11-boundary_value_problems.ipynb">nbviewer</a>, 
    <a href="https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=lectures%2F11-boundary_value_problems.ipynb">binder</a>, 
    <a href="https://raw.githubusercontent.com/valenpe7/numerical_methods/master/lectures/11-boundary_value_problems.ipynb" download>ipynb</a>
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

-->

</section>

The study materials are evolving quickly. Therefore, if you find any mistake, please submit an [issue](https://github.com/valenpe7/numerical_methods/issues) to the GitHub project repository.

### Recommended literature:

[1] W. H. Press, B. P. Flannery, S. A. Teukolsky, V. H. Vetterling, *Numerical Recipes: The art of scientific computing*, Cambridge University Press, Cambridge, 3rd edition 2007 (available at [http://www.numerical.recipes/oldverswitcher.html](http://www.numerical.recipes/oldverswitcher.html)).

[2] A. Ralston, P. Rabinowicz, *A First Course in Numerical Analysis*, McGraw-Hill 1965 (reprinted by Dover Publications, 2001).

[3] R. W. Hamming, *Numerical Methods for Scientists and Engineers*, 2nd edition, Dover Publications 1986.

### Useful links:

- [Main webpage of the course](http://kfe.fjfi.cvut.cz/~vachal/edu/nme/)
- [Guidelines to lectures and seminars](http://kfe.fjfi.cvut.cz/~limpouch/numet/NMECvic.pdf)
- [Outline of lecture](http://kfe.fjfi.cvut.cz/~limpouch/numet/sylnum.html)
- [Transparencies of lectures](http://kfe.fjfi.cvut.cz/~limpouch/numet/lecnum.html)
- [References to numerical methods](http://kfe.fjfi.cvut.cz/~limpouch/numet/refnum.html)
- [Further study materials](http://kfe.fjfi.cvut.cz/~vachal/edu/nme/cviceni/index.html)

