# Izhikevich Neuron Simulation

This project implements the Izhikevich neuron model to simulate the membrane potential dynamics of a biologically realistic spiking neuron.

## Objective
To understand how external input current influences neuronal firing behavior using computational modeling.

## Model
The Izhikevich model is described by the following equations:

dv/dt = 0.04v² + 5v + 140 − u + I  
du/dt = a(bv − u)

When the membrane potential reaches a threshold, a spike is generated and the variables are reset.

## Tools Used
- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Results
The model successfully demonstrates regular spiking behavior. Increasing the input current
leads to a higher firing frequency, while lower current reduces spiking activity.

## Motivation
This project was undertaken to explore computational approaches to understanding neuronal dynamics,
bridging biology with data-driven modeling.
