# Description
As an international company, Bissan Exports are intentional about the travel destinations of their employees.<br> They study these visited locations - understanding the people and the environment - in order to know<br> what products to export to these regions.<br><br>
There already exist some travels dataset by their employees stored in a google drive. The demography <br>information for the regions travelled exists in some other location in a JSON file. The URL is provided<br> for your use. Lastly, details about the employees’ travel stipend exist in their database.<br><br>
The datasets from the three sources (postgres database, JSON file and CSV file) need to be cleaned and transformed <br>to answer business questions below.

# Dataset
Travel Details (CSV): https://drive.google.com/uc?id=1muwnik-uFGTKBdHmcQN5z68rD7qmdG-b

US Demography (JSON): https://public.opendatasoft.com/api/explore/v2.1/catalog/datasets/uscities-demographics/exports/json?lang=en&timezone=Africa%2FLagos


## Tools
<ul>
    <li>Python</>
    <li>Pandas</>
    <li>Psycopg2</>
</ul>

## Steps
<ul>
    <li>Extract Data</li>
    <li>Clean Data</li>
    <li>Transform Data</li>
</ul>

## Business Questions
<ol>
    <li> How many employees spent above their given stipend? Extract the name of the employee, the assigned stipend, and the actual amount spent.</li>
    <li> What location was most visited?Return the name of the City, State, and the total visits.</li>
    <li> How much was spent on travels by Troy Tippett? What state did he visit? What are the average household size and most common race found in that city?</li>
    <li> How many of their employees visited Florida? What are the male and female population statistics?</li>
    <li> Which state has the most veterans? Which employees travelled there?</li> 
    <li> What is the gender breakdown of the most populated city?</li> 
    <li> How many veterans exist in the state visited by Evan Clarke? Q8. What month has the most travels?</li>
</ol>