---
layout: post
title:  How to launch the jupyter notebooks
date:   2017-10-27
categories: software
tags: notebook
---

You will first need to connect to our analysis computer (check post in this web site)

Start a terminal session. You may already see the **terminal** icon at the top, or bottom of your screen

![launch terminal](/assets/how_to_launch_python_notebook/click_terminal.png)

or, if you don't see the icon, launch it via the list of programs

![launch terminal](/assets/how_to_launch_python_notebook/start_terminal.png)

Then, in the terminal window, type the following command

> /SNS/users/j35/bin/start_jupyter notebooks

This will perform the following processes:
 - configure the system to run the right python environment
 - bring all the notebooks into your environment
 - move to the notebook location
 - start the jupyter notebook session

![top folder of jupyter notebook](/assets/how_to_launch_python_notebook/start_jupyter_session.png)

To test your system, start any of the notebook (files ending by *pynb*) by clicking its name

![click notebook](/assets/how_to_launch_python_notebook/click_notebook.png)

and make sure the **kernel** is named **Python [default]**

![default kernel](/assets/how_to_launch_python_notebook/python_kernel_default.png)

If the kernel is NOT **Python [default]**, you need to change it by going to

 *Kernel > Change kernel > Python [default]*

![new kernel](/assets/how_to_launch_python_notebook/change_kernel.png)