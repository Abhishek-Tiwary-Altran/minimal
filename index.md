
# boa-interface-functions

This example implements a possible instrumentation of a basic CFD simulation, run with OpenFOAM, with BOA.

The simulation models the flow around a cylinder, where the control variables are the flow's inlet velocity, initial pressure, turbulent kinetic energy, dissipation rate, and wall velocity. The objective is to minimize the turbulent kinetic energy at a point in the cylinder's wake (coordinates x=2, y=0=z).

This example works against any hosted BOA services.

# IBM Bayesian Optimization Accelerator 

BOA is a statistical framework that uses machine learning to model and mathematical acquisition functions to minimize an arbitrary objective function. Our team has productized the IBM Bayesian Optimization numerical library to be delivered as appliance (IBM Power 9 server + BOA Software stack), a machine learning tool developed by IBM Research, reducing the number of simulations needed to reach the optimal configuration point for chip-to-chip communication.


