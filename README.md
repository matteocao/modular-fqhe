# modular-fqhe

A very computational approach to mudular cirves and FQHE (fractional quantum hall effect).

## Requirements
You needd to have docker installed in your machine. Then,  pull the docker with
```
docker pull sagemath/sagemath
```
and run it as jupyter notebook from the root folder by
```
docker run -v "${PWD}:/home/sage/volume" -p8889:8888 sagemath/sagemath:latest sage-jupyter
```
Visit `http://localhost:8889` to start playing with the notebook (you will find it in the `/volume` folder). Also, check your terminal to get the *token*!

## Run and experiment

Once you have run the SageMath docker, simply run the notebook from the browser.

The notebook is structured to be read from top to bottom, but you can also jump directly to the section of interest.

I do not claim anything on the algorithms: they are standard tools in SageMath. My effort is to bring together the main ideas via examples and intuitive reasoning.

## Contributing

If you think there are missing sections or some explanations are simply not well written (or wrong!), please let me know!
