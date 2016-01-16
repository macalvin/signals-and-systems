This repository contains Julia notebooks for visualizing various concepts taught in ECSE 303, Signals and Systems at McGill University. The following software is needed to run these notebooks:

* [Julia] \(with package [Gadfly])
* [Jupyter]

[Jupyter]: http://jupyter.org/
[Julia]: http://julialang.org/
[Gadfly]: http://dcjones.github.io/Gadfly.jl/

It is also possible to run these notebooks in the cloud using the [Juliabox] service. For the course, we recommend using Juliabox because you do not have to worry about installing anything.

[Juliabox]: http://www.juliabox.org/

##Getting started with JuliaBox

1. Sign in to JuliaBox (http://www.juliabox.org/) with a Google account. 
2. Click on the **Sync** tab on the top menu bar of JuliaBox
3. Add the git repository by copying the following link  into the **Git Clone URL**: https://github.com/mcgill-303/signals-and-systems.git The other boxes should fill in automatically. Press the **+** to accept. If the other details are not filled in, set **Branch** as *master*, **JuliaBox Folder** as *signals-and-systems*. 
  ![sync.jpg](img/sync.jpg)
4. Return to the **IJulia** tab and the *signals-and-systems* directory should be visible.
5. In the *signals-and-systems* directory, click on the *notebooks* directory, and then click on the notebook named `00-Initialize.ipynb`
6. Wait for the kernel to finish connecting. The status is shown in a box left of the kernel version `Julia 0.4.2`. If there is no box, the kernel is loaded.
  ![kernel_status.jpg](img/kernel_status.jpg)
7. Run all cells by clicking on the file menu **`Cell>Run all`**. It takes a few minutes to download and install the  required packages. When a cell is being executed, there is a **`[*]`** on the left side of the cell. Do not be alarmed if you see some warnings & errors like this.
  ![error.jpg](img/error.jpg)
8. Restart the kernel by clicking on the file menu **Kernel>Restart**
9. Rerun all the cells **Cell>Run all**. This time there should be no errors; warnings can be ignored.

The `00-Initialize.ipynb` needs to be run only once. After that, you are ready to explore other notebooks! Click on any notebooks, and then click on **`Cell>Run all`** in the file menu. 

## Included Notebooks

1. **Signal-Algebra.ipynb**: Illustrates addition and multiplication of two signals. 
2. **Convolution**: Illustrates convolution of two signals.

## About this project

These notebooks are developed by [Calvin Ma] and [Aditya Mahajan] with financial support provided by McGill Engineering Undergraduate Support Fund (EUSF).

[Calvin Ma]: https://github.com/macalvin
[Aditya Mahajan]: https://github.com/adityam


