# jupyter-test-automation

## Extending Test Automation Using Jupyter Notebooks
Launch using Binder to view interactive slides 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brendanconnolly/jupyter-test-automation/main?filepath=Slides.ipynb)

*note: Selenium example will not work on binder

## Language Examples

Inside each language folder there is a `Dockerfile` and `docker-compose.yml`

To run the examples from the console run `docker-compose up --build`
*the `--build` flag is only required the first time


## Use with Selenium

For exploratory testing purposes the browsers a launched without the headless options.

To be able to interact with the browser and run the notebooks inside a docker container an instance of Selenium Grid is required. 

Docker Compose is used to setup the notebook server as well as a selenium grid host.

Once the containers are up and running, executing the `start_local_node_mac.sh` script will register a local Selenium Node with the grid. 





