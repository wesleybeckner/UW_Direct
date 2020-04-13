<a id='top'></a>

# There are Two Projects Here

Project 1 is more optimization/hardcore machine learning focused and Project 2 has more to do with data visualziation.

I think both useful learning cases and useful business cases -- It just depends on what is of interest.

# Corian Product Wheel Project 

## What does the model do?

The Product Wheel Tool modeled in Excel Solver or Python determines for each SKU the ‘duration between campaign’ (relates to campaign size) that will give the least overall cost product wheel costs (transition + inventory carrying cost)

Objective:  Minimize Product Wheel Cost at SKU level within supplied constraints

Method: Optimize unconstrained first. Then, apply constraints (e.g. target inventory) to get a realistic solution

Key Output from the model:  How often to make a SKU i.e. duration between campaigns

Unfortunately we don’t have inventory carrying cost data. So we will only be minimizing transition costs

    
# Product Margin Dashboard

## What does the dashboard do?

The Gendorf Dashboard allows a production engineer to pull on key variables/levers. The idea is to onboard this as part of a site assessment

Objective:  Create a datadashboard that is user friendly – visually appealing

Method: Python/Plotly, PowerBI, Tableau, Excel w/  Powerview

Key Output from the dashboard:  EBITDA related KPIs 

 
[app-site](http://www.gendorf-dev.herokuapp.com/)

user: gendorf

pass: assessment

This is an [product characterization dashboard](https://gendorf.herokuapp.com) demo using [Dash](https://plot.ly/products/dash/) 

## Getting Started

### Running the app locally

First create a virtual environment with conda (or venv) and activate it.

```

conda create -n <your_env_name> python==3.7
source activate <your_env_name>

```

Clone the git repo, then install the requirements with pip

```

git clone https://github.com/wesleybeckner/gendorf.git
cd gendorf
pip install -r requirements.txt

```

Run the app

```

python app.py

```

## About the app

This is an interactive app to assess product margins and subsequent impact on annualized EBIT for manufacturing


## Built With

- [Dash](https://dash.plot.ly/) - Main server and interactive components
- [Plotly Python](https://plot.ly/python/) - Used to create the interactive plots
  
