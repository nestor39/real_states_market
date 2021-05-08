# Real States Market

This code was created with the purpose of building an instant one -click service for people to buy properties and rent them. I used several tools, which can show a map of the city of San Francisco with interactive options and you can even zoom in on the map, as well as being able to see a list of neighborhoods that have good buying and/or renting potential. 

## Technologies

 os

pandas

plotly.express 

hvplot.pandas

pathlib

dotenv

## Instalation


In order to open and run this program you have to follow these steps:


Go to my repository in GitHub and open the repository called "financial_retirement_planning"
![real_states_git_jpg](https://user-images.githubusercontent.com/80844686/117373431-0d78ce80-ae80-11eb-917a-3c349bedda60.jpg)



Copy the repository's link


Open Git Bash in your computer 

![git_bash](https://user-images.githubusercontent.com/80844686/115638940-40d82c80-a2c8-11eb-816a-e991b245cd88.jpg)


clone the repository by typing "git clone" and paste the link "git@github.com:nestor39/real_states_market_6.git"

![git_clone_real_states](https://user-images.githubusercontent.com/80844686/117373307-d7d3e580-ae7f-11eb-84e7-310633600bde.png)




After cloning the repository, activate the Conda development environment, by typing "conda activate dev" and then run the following code:


conda install -c anaconda requests

pip install python-dotenv

conda install -c plotly plotly=4.13.

conda install -c pyviz hvplot

jupyter labextension install jupyterlab-plotly@4.13.0

jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.13.0

jupyter labextension install @pyviz/jupyterlab_pyviz





After installing the tools above 

Type "jupyter lab" in your Git Bash(it will open a tab in your explorer)



Open the file "san_francisco_housing.ipynb" and you are going to see the code.

But before running the code you should open a new tab in your browser, paste this link "https://account.mapbox.com/auth/signup/" and create your account with mapbox



Get the mapbox API access token and secret keys

![6-0-mapbox-signup-page](https://user-images.githubusercontent.com/80844686/117371473-c937ff00-ae7c-11eb-8452-bf7111e7018f.png)

![6-0-mapbox-api-token](https://user-images.githubusercontent.com/80844686/117371485-cccb8600-ae7c-11eb-9ba3-7dc8ca232ba8.png)


Go back to jupyter lab, create a file and rename it as ".env" inside this file copy and paste:
  
 MAPBOX_API_ACCESS_TOKEN = "Your mapbox API access token here"

Save it

Push play

## Results

This code is going to show you many superpower tools with interactive characteristics:

![housing_units_by_year_jpg](https://user-images.githubusercontent.com/80844686/117371580-f97f9d80-ae7c-11eb-95af-99b15a73bf25.jpg)

![plot_sales price_by_square_foot_and_gross_rent](https://user-images.githubusercontent.com/80844686/117371612-07cdb980-ae7d-11eb-889f-b40f3407b515.jpg)

![san_francisco_by_neighborhood](https://user-images.githubusercontent.com/80844686/117526833-a4c34c00-af7c-11eb-8ea5-f2cca81c15a1.jpg)



## Examples
The following image shows a diagram of the financial retirment planning file:

![real_states_market_excalidraw_jpg](https://user-images.githubusercontent.com/80844686/117371559-f1bff900-ae7c-11eb-9296-1edb04ea70c5.jpg)


## Contributors

This project was made with helpful contribuitions from Berkeley Fintech Bootcamp members; Siege and Joel Gonzales. Joel Gonzales was of particular assistence when it came to improving the code.

I also utilized the AskBCS Learning Assistent in order to fine-tune my project.


This code was written by Nestor Ramirez.

email: nestorramirez3994@gmail.com

Linkedin: (https://www.linkedin.com/in/nestor-ramirez-cuadro-375654209/)

## License
MIT
