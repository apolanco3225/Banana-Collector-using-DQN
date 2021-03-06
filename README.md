# Banana Collector using Deep Reinforcement Learning 

For this project, it's trained an agent to navigate (and collect bananas!) in a large, square world.

<img src='https://s3.amazonaws.com/video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif' align='center'>

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

    
### Instructions
* Set up your environment: 

	nity has to be installed on your system. Run:
	```
	source ./install.sh
	```

	to install python dependencies. Then you should be able to run jupyter notebook and view navigation_drl.ipynb. 

* Install Udacity's environment



	* To set up your python environment to run the code in this repository, follow the instructions below.

	1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```

	2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.  
		- Next, install the **classic control** environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
		- Then, install the **box2d** environment group by following the instructions [here](https://github.com/openai/gym#box2d).

	3. Clone the repository (if you haven't already!), and navigate to the `python/` folder.  Then, install several dependencies.
	```bash
	git clone https://github.com/udacity/deep-reinforcement-learning.git
	cd deep-reinforcement-learning/python
	pip install .
	```

	4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.  
	```bash
	python -m ipykernel install --user --name drlnd --display-name "drlnd"
	```

	5. Before running code in a notebook, change the kernel to match the `drlnd` environment by using the drop-down `Kernel` menu. 

	<img src='https://user-images.githubusercontent.com/10624937/42386929-76f671f0-8106-11e8-9376-f17da2ae852e.png'>


## Run
Follow the instructions in navigation_drl.ipynb to get started with training the agent.
