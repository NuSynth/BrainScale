# DEATHNET
This repository is for a neural network inspired by the components of the human brain, and using known neuron computational models of human neurons.


First; this repository will be used for neuron computational units of human neurons. Then neural networks of these units will be stored here that represent the different components of the human brain, but with far fewer neurons and synapses.

After the units of neural networks are built, they will be networked together to create one functional network.



The main goal of this project is to create a simulation of a human mini-brain. The Wernick and Broca areas of the brain will later be able to be networked with an LLM in order to increase it's intelligence, since the model of the brain itself being built here is not going to be to scale of the human brain. Between the LLM augmentation and the biologically inspired structure of the mini-brain, I believe this will be actual AGI.


The current goal for the scale of the mini-brain is 19,000 neurons and 150,000,000 synapses, which is obviously only a small fraction of the size of the average human brain.

# Languages
- The Verilog language is going to be utilized so that I can test the computational neuron models within simplified networks that I build. These simplified networks of human neuron computational models will run on FPGA hardware. The Spartan-7 FPGA chip is estimated to be able to process a neural network of between 500 to 1500 neurons with 200,000 synapses, and is the chip I am going to use. An estimated 750 Spartan-7 FPGA boards are required to run the completed mini-brain. The simulation of the brain will be between 2,000 to 200,000 times the speed of a biological brain. The power requirement at max throughput is estimated to be ~7.5kW. That is cheap enough for me to run the entire thing locally and run tests with a locally ran LLM on a GPU networked with the FPGA's Wernick's and Broca's areas of the simulated brain in order to augment its' intelligence.
