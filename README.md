[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1000436.svg)](https://doi.org/10.5281/zenodo.1000436)


## About

[container_for_lsm_in_Mila_basin](https://github.com/aminevsaziz/container_for_lsm_in_Mila_basin) is Docker image repository made for "Landslide Susceptibility Mapping In Mila Basin" project available under [lsm_in_Mila_basin](https://github.com/aminevsaziz/lsm_in_Mila_basin) repository.



## Issues

Feel free to fork the repository and submit issues (send me pull requests as needed). If git isn't your thing, e-mail me at [abdelaziz.merghadi@gmail.com](abdelaziz.merghadi@gmail.com) for any enhancements or corrections.


## Maintenance and Updates

This image is actively maintained.  This means that while an effort is made to preserve the general function of the image over time, both the Dockerfile and the resulting image are subject to some change over time.  In particular:

- Image is regularly re-built on Docker Hub whenever base image changes, starting with changes to `debian` Docker image.  This is the rough equivalent of running `apt-get upgrade` on `debian`, since all `apt-get` commands are re-run and will pull in the most current sources.  This allows the image to receive security updates to any packages installed from the `debian` repositories, but will not in general change the versions of any software and is very unlikely to break anything.

- The Dockerfile itself is subject to change, to improve performance, ease of use, readability, or other concerns raised in the issues.  These changes should also not alter the general behavior of R or R packages on the image.  These changes can be seen in the git history.


## License ##

The files in this repository are licensed under the GPL-3.0.
