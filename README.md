# rces-final-project
My final project repository for RCES

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/janeeleven/rces-final-project/HEAD)

Scientific Question: Does the concavity of the surface topography of an ice rise reflect the velocity field of its internal layers?

Dataset: Model output generated from ElmerIce (https://elmerice.elmerfem.org). Data hosted on Google Cloud Storage (https://console.cloud.google.com/storage/browser/ldeo-glaciology/elmer_janie/output_vals)

I will convert the model output from its native VTU format and load it into Python so that data such as surface profiles and velocity fields are easy to access. I will fit profiles to lines of equal velocity in the velocity field. I will then compare properties such as concavity and distance between inflection points and peaks of the surface profiles and velocity profiles for each time step in a model run. 