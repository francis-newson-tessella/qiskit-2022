# Quantum computing with Qiskit

This repository contains code to support the 
"Quantum computing with Qiskit"
session at the 2022 Hybrid Intelligence conference.

## Get Started

Install python dependencies using `pipenv`. In the current directory, do:

    pipenv install

Load additional config from `.envrc`
If you're using [direnv](https://direnv.net/), this will be picked up automatically
or you can run:

    source .envrc

Now you can run juypter lab with:

    pipenv run jupyter  lab

or 

    make jl

## Structure

- [Notebooks](./notebooks/README.md) - jupyter notebooks. See nested READMEs for details.
- [Makefile](./Makefile) - handy commands
- [qiskit-conf](./qiskit-conf/settings.conf) - settings for qiskit