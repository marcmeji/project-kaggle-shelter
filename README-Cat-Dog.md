<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# CAT/DOG
*[Hernando Cardenas]*
*[Laura Jimenez]*
*[marc mejias]*
*[jordi marsal]*

*[datapt-bcn, Barcelona & 2019]*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
Este proyecto se trata de elaborar un modelo de machine learning para poder predecir el destino final de los animales abandonados en un refugio de austin texas. 

<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions
* ¿que probabilidad de que el outcome del animal sea eutanasia?
* ¿saber la diferencia que hay en los outcomes entre gatos y perros?
* ¿saber la tasa de adopcion dependiendo si estan esteriizados o no?
* ¿es real que los animales ya esterilizados tienen una tasa de adopcion mas alta?
* ¿los animales menores de 1 año tienen mayor tasa de adopcion?
* ¿es real que los gatos negros y blancos son mas apetecidos en el mes de octubre para motivos esotericos?


<a name="dataset"></a>

## Dataset
*Este data set fue descargado de kaggle https://www.kaggle.com/c/shelter-animal-outcomes.
   * los datos a manejar son los siguientes y cada uno significa lo siguiente
   * AnimalID = object Type
   * Name = object Type
   * DateTime = object Type
   * OutcomeType = object Type
   * OutcomeSubtype = object Type
   * AnimalType = object Type
   * SexuponOutcome = object Type
   * AgeuponOutcome = object Type 
   * Breed = object Type
   * Color = object Type
   

<a name="cleaning"></a>

## Cleaning
Como encontramos columnas que tenian una gran cantidad de valores nulos los eliminamos del dataset, en el caso de OutcomeSubtype mas del 50% eran nulas y en el caso de Name esta variable no aporta valor al analisis.
Al ver el bar plot dela variable breed se encontraron 1600 valores diferentes asi que se elimina la columna.

<a name="analysis"></a>

## Transformation
* la columna DateTime se pasa de formato Object a formato date time y se cambia el nombre de la columna a simplemente date.
* la columna AgeuponOutcome se unifico a dias y se transformo a numerica.
* se reducen las categorias de colores de 366 a 6.
*



<a name="transformation"></a>

## Analysis
* EDA
*

<a name="model-training-and-evaluation"></a>

## Model Training and Evaluation
*Include this section only if you chose to include ML in your project.*
* Describe how you trained your model, the results you obtained, and how you evaluated those results.

<a name="conclusion"></a>

## Conclusion


<a name="future-work"></a>

## Future Work
* incluir el analisis por razas.
* 
<a name="workflow"></a>

## Workflow
* Import data
* Preprocesamiento
* EDA
* Featuring Engieneering
* Model Creation
* Documentation

<a name="organization"></a>

## Organization
* se formaron 2 grupos uno encargado de la documentacion y el otro encargado del preprocesamiento.
*


<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/ljgoico/project-kaggle-shelter)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/en)  