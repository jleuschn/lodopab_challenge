# LoDoPaB-CT challenge utilities

This repository contains utilities for the
[LoDoPaB-CT challenge](https://lodopab.grand-challenge.org).

The functions in ``challenge_set.py`` help accessing the observation
data from which the challenge asks to compute reconstructions.

To save the reconstructions to files, use the function ``save_reconstruction()``
from ``submission.py``.
A packed zip-File of the written files can be uploaded as a submission to the
challenge website.
