# Sniffer Channel Assignment in Wireless Networks

Brief Description:

Accurate and timely estimates of wireless network conditions and performance characteristics can yield better performance in a number of applications such as network resource management,wireless advisory,troubleshooting etc.However,utilization of multiple contiguous or non-contiguous channels or bands for estimation gives rise to the Sniffer-channel assignment problem.Sniffer-channel assignment with no prior knowledge of user activity is closely related to the multi-armed bandit problem (MAB) which can be optimized by Sequential Learning. While prior works have explored ways to use variants of the Upper Confidence Bound(UCB) algorithm for this purpose, they have assumed the users are static. We analyze two algorithms: the discounted UCB and the sliding-window UCB to cater to the
wireless network with non-stationary users i.e mobile users.

The notebook contains the implementation of the above mentioned problem.
Please use the steps mentioned below to execute the python notebook.

Installing IPython Notebook
+++++++++++++++++++++++++++++
$ sudo apt-get install ipython-notebook python-matplotlib
Or
if you want to install using 'pip', then you can install IPython as follows.
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
$ pip install ipython[notebook]

Starting IPython
++++++++++++++++++++++

To start IPython in terminal:
++++++++++++++++++++++++++++++++++
$ ipython Sequential_Learning_for_Multi_Channel_Wireless_Network_Monitoring_With_Channel_Switching_Costs.ipynb

or

jupyter Sequential_Learning_for_Multi_Channel_Wireless_Network_Monitoring_With_Channel_Switching_Costs.ipynb

Once IPython is running sucessfully, a browser window will automatically open or
point your web browser at http://localhost:8888 to start using IPython notebooks.
