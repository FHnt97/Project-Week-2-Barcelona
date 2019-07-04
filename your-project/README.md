<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Title of My Project
*Lucas Akesson, Fabia Höhne*

*Data, Barcelona, Summer 2019*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description

This project encompasses the analysis of a data set based on a hypothesis/question on the city of Barcelona. 
For this project, our group will base on a analysis of a topic in the cathegory: Economics and Busines. 
We have chosen to narrow down this cathegory by focusing on the tourism sector of the city of Barcelona, taking the occurancy rates of hotels as our main point. 



<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions
Our question therefore goes as follows:

1.What is the proportion of tourist staying in hotels vs. other accommodations changed in the Barcelona over of Catalunya? How has this changed over the last two/three years?

2. Is there a relationship between the country of origin of poeple and weather or not they stay in hotels? 
        - initially only looking at data from 2018 - BONUS: expand to timely comparison
        
3. Is there a trend between the GDP of a country an weather the tourists stay in hotels or not?
        - initially only looking at data from 2018 - BONUS: expand to timely comparison
        
BONUS:
We are takeing the assumption that, out of the total number of tourists in Catalunya, the proportion of tourists who visit other Comarques and that who visit Barcelona is equal for every country of origin. This may not be true, as people from specific countries might have a preference to visit different types of destinations. 
(E.g. Americans come to Barcelona, whilst the French prefer Girona (this statements is NOT based on a data analysis, and serves only to clarify the assumption))

4. Comparing the numbers of tourists per desitination of another region of Catalunya and 



<a name="dataset"></a>

## Dataset
Where did you get your data? What dataset did you use or did you build your own datset. Provide links to the data if available.

Data sets where retrieved form:
        - IDESCAT:
            The  Generalitat de Catalunya Statistical Institute
            (Data on Foreign tourists. By country of residence (under "Short-term economic indicators, Tourism")
            https://www.idescat.cat/indicadors/?id=conj&n=10306&lang=en&col=1
            
        - Ajuntament de Barcelona:
            Estadistiques, Encuesta de ocupación hotelera (EOH) en la ciudad de Barcelona.
            http://www.bcn.cat/estadistica/angles/dades/economia/teoh/actual/r2018.htm
            
        - Ajuntament de Barcelona: 
            Turisme, Informació i dades estadístiques sobre el perfil dels turistes que pernocten a la ciutat de Barcelona.
            https://ajuntament.barcelona.cat/turisme/perfil-dels-turistes#grafica_1
            

As the data found on this topic was a bit more limited than we expected, we decided to make folowing assumptions:

        - The proportion of tourist from Catalunya that go to Barcelona is equal for all tourist of all nationalities.

        

[Dataset]() 

<a name="workflow"></a>

## Workflow
Outline the workflow you used in your project. What were the steps you went through?

1. Define question
2. Find data on topic and see which data works
3. Plan out possible databases, what relationships they have and how these would be used to analyse the data - identlify primary keys, etc. 
4. Transform data into useful format and open in python to create DB. 
5. Clean and Analyse data.
5. Upload tables into SQL based DMS, refine data searches and results. 
6. Ensure that database can be accessed externally, create slides, update readme.md

<a name="organization"></a>

## Organization
How did you organize yourself? Did you use any tools?

google - data search
excel - data copy/pasting form websites and creating .csv files
jupyter notebook - for data manipulation (PANDAS) and an organised layout of steps in the manipulation code
mysql workbench and mysql pro - to create a cloud database with foreign access


<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/FHnt97/Project-Week-2-Barcelona)  
[Slides](https://slides.com/fabiahnt/barcelona-tourism/fullscreen)  
[Trello](https://trello.com/b/lEOyUYEz/project-2)  