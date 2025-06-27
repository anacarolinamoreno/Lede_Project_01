# How much does it cost to travel to China cost?
(May 2025)
<br>
*Warning: the data and the LLM prompts are in Portuguese, but you can survive this.*

### What is this project?
This is my first project for the Lede Data Journalism Program at Columbia University. On May 2025, my mother and I travelled around China. Before I went, a friend had asked me how much it costs to travel there. So I boarded the plane willing to find out.

### Objective:
To catalog how much my mother and I spent on a vacation trip to China while I practice Python, mapping and HTML+CSS.

### Steps:
1- From raw data to a dictionary with minimum typing
<br>
2- LLM fact-checking for accuracy
<br>
3- Data analysis
<br>
4- Dataviz
<br>
5- Presentation

#### Step 1: from raw data to a dictionary with minimum typing
The source of the data is far from tidy and structured: a note I kept on my phone. Whenever there was a 15 minute gap in a car, train or airplane, I would write in Portuguse what we did, how much it cost and who paid for it (just to control the expenses from each paying source) for each day, and which city we were in that day.

It had only a minimum attention to stardards and highly subjected to my level of energy, memory and desire to keep track of our expenses ([see it for yourself here](00_raw/raw_data.txt)). But hey, at least it was digital text.

Because I wanted to practice dataviz, not data cleaning, I decided not to spend too much type coding my way from a crazy txt file into a Python dictionary. So, sticking with the theme, [I asked DeepSeek-R1 for help](01_prompt/prompt.md).

And [it pretty much worked](00_raw/china_raw.py)! I changed the name of the object from "gastos_viagem" to "expenses" and stored it into a .py file. Then I wised up and asked it to turn the dictionary [into a json file](00_raw/china_raw.json).

#### Step 2: LLM fact-checking for accuracy
After I got the raw data in the appropriated format, it was time to check its content. I chose to use pandas straight away. [Here's the jupyter notebook](03_notebooks/00_check.ipynb) for this step.

#### Step 3: Data analysis


