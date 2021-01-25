# Portfolio

## Themes

This portfolio includes work where I was the primary or sole contributor unless otherwise noted. 

* [ML/Computational Chemistry](#compchem)
* [ML/Computer Vision](#cv)
* [Reinforcement Learning](#rl)
* [Evolutionary Strategies](#es)


## Computational Chemistry
<a name="#compchem"></a>

* **[DockRL](https://github.com/rivesunder/DockRL).**
Molecular docking wrapped in a reinforcement learning environment with optimization of the protein-ligand re-docking problem via covariant matrix adaptation evolution strategies.
* **[RamaNN Chemometrics](https://github.com/rivesunder/ramann-metrics).**
A branched MLP for classification and dimensionality reduction for Raman spectra. A non-linear alternative to PCA/LDA chemometrics workflows.
* **[MetabolSim (2011)](https://github.com/rivesunder/metabolsim).**
A numerical simulator for metabolic networks described in a netlist with Michaelis-Menten kinetics. My first Python project.
* **[Circular Dichroism Solver (2010)](https://github.com/riveSunder/MetabolSim/blob/master/circDichroismSolver.m).**
Written in MATLAB, I wrote this simple hill-climbing algorithm to solve circular dichroism spectra from a protein structure lab course. Perhaps my first machine learning project.

## Computer Vision
<a name="#cv"></a>
<em>Public work</em>

* **[Differentiable Cellular Automata](https://github.com/riveSunder/dca)**. 
A project exploring the confluence of ideas from differentiable programming, neural networks, and cellular automata, inspired by Distill's thread on [Differentiable Self-Organizing Systems](https://distill.pub/2020/selforg/).
* **[CuttleVision](https://github.com/riveSunder/cuttleVision)**. 
This project investigates a possible mechanism for color perception via chromatic aberration in cephalopods, described by ([Stubbs and Stubbs 2016 (pdf)](https://www.pnas.org/content/pnas/113/29/8206.full.pdf)). The Fourier optics simulation of plausible cephalopod vision is described in a [blog post](https://thescinder.com/2016/07/25/through-the-strange-eyes-of-a-cuttlefish/) while the machine learning side of things is described [here](https://thescinder.com/2017/10/10/introducing-ceph-o-vision/). 
* **[fun-with-gans](https://github.com/riveSunder/fun-with-gans)**. 
Just a simple DCGAN implementation applied to mushroom images from unsplash/pixabay. 
* [pseudo-deconn](https://github.com/riveSunder/pseudo-deconn). 
A "w-network" for pseudo-deconvolution of microscopy images. 
* **[Digital Digit Recognition](https://github.com/riveSunder/digitalDigitRecognition)**. 
A classifier trained on hand-signed numbers from 0 to 9 acquired with a chest-mounted GoPro camera. This project was built in 1.x TensorFlow.
* **2-headed CNN for 2-stage training and siRNA classification (Recursion rxrx1 dataset, keras) [Kaggle Notebook](https://www.kaggle.com/rivesunder/recursion-2-headed-cnn-and-training-in-2-stages)**. 
This notebook demonstrates several training schemes for classifying fluorescence microscopy images of several cell lines with ~1000 different siRNA knockdown categories.
* **Hand-Written Digit Recognition, with AlexNet (keras) [Kaggle Notebook](https://www.kaggle.com/rivesunder/topless-alexnet-0-9947) and Learning Rate Optimization [Kaggle Notebook](https://www.kaggle.com/rivesunder/optimizing-learning-rate-in-keras)**. 
Classifictation of the MNIST dataset with a replica of AlexNet built in keras. 
* **Learning ASL Number Signs with a LeNet-5 (keras) [Kaggle Notebook](https://www.kaggle.com/rivesunder/learning-asl-signs-with-lenet-5)**. 
Classifying images from th [Sign-Language MNIST](https://www.kaggle.com/datamunge/sign-language-mnist) dataset on Kaggle. 
* **Aerial Cactus Identification with DenseNet121 (keras) [Kaggle Notebook](https://www.kaggle.com/rivesunder/headless-densenet-with-keras)**. 
Identifying the presence or absence of cacti in aerial images, essentially a line detector. This notebook was the basis for achieving 100% accuracy in Kaggle's [Aerial Cactus Identification](https://www.kaggle.com/c/aerial-cactus-identification) challenge. 

### Reinforcement Learning and Evolutionary Strategies
<a name="#rl"></a>
<a name="#es"></a>

* **[Boostrapping Evolutionary and Developmental Learning](https://github.com/rivesunder/bevodevo)**. 
`bevodevo` is a resource for studying and experimenting with a range of evolutionary and developmental algorithms, currently with an emphasis on episodic reinforcement learning tasks.
* **[Policy Generating Evolved Networks](https://github.com/riveSunder/pgens)**. 
Training meta-policies that generate multiple agent policies using evolutionary strategies.
* **[OpenSafety](https://github.com/riveSunder/OpenSafety)**. 
A reinforcement learning environment with several safety-related robotics control tasks, using the physics simulator PyBullet. [SafeAgetns](https://github.com/riveSunder/SafeAgents) implements evolutionary strategies with multiple (reward and safety) fitness consideration. 
* **[rl-simple-games](https://github.com/riveSunder/rl-simple-games)**. 
Text-based reinforcement learning environment for simple games Hexapawn, Sim, and Tic-Tac-Toe (aka Naughts and Crosses). 
* **[RobothorAgents](https://github.com/riveSunder/RobothorAgents)**. 
A repository demonstrating computer vision off-task/pre-training for the [Robothor](https://ai2thor.allenai.org/robothor/challenge/) challenge environment from the [Allen Institute for AI](https://allenai.org/). 
* **[RocketGym](https://github.com/riveSunder/RLRocketGym)**. 
A rocket-themed RL environment with tasks like rocket landing and balancing, using the permissively-licensed PyBullet physics simulator.
* **[Synaptolytic Learning](https://github.com/riveSunder/synaptolytic-learning)**. 
Evolution-based learning algorithms based on random and Hebbian-informed neural pruning. 
* **[Learning Rubik's Cube with Reinforcement Learning](https://github.com/riveSunder/lrcuberl)**. 
A text-based Rubik's cube environment with an implementation of DQN ([Mnih _et al. 2014](https://deepmind.com/research/publications/human-level-control-through-deep-reinforcement-learning))


