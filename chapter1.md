---
  title: "Measures of occurrence"
  description: "Distinguish among counts, ratios, proportions, and rates.\nDefine and estimate person-time.\nCalculate incidence and prevalence."
  v2: true

---
## 1.1 Prevalence of influenza

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: 4fd567cce6



```

Prevalence is the proportion of people with a disease or condition in a population at a certain time. Prevalence is calculated as the count of cases over the population at risk.

`@instructions`
Calculate the prevalence of influenza in a population of 5000 university students living on campus in January 2018. During that time, 100 of them had influenza.

`@hint`
- Type this line next: cases <- 100

`@pre_exercise_code`
```{r}
# Load datasets and packages here.
```
`@sample_code`
```{r}
# Remember that prevalence = case count / population count.
# Assign 5000 to a variable called "population".
population <- 5000

# Assign 100 to a variable called "cases".


# Calculate prevalence by completing the formula.
prevalence <- cases / 

# Print the result 

```
`@solution`
```{r}
# Remember that prevalence = case count / population count.
# Assign 5000 to a variable called "population".
population <- 5000

# Assign 100 to a variable called "cases".
cases <- 100

# Calculate prevalence by completing the formula.
prevalence <- cases / population

# Print the result 
prevalence
```
`@sct`
```{r}
success_msg("Nicely done! Prevalence is an important measure of disease burden.")
```






---
## Interpretation

```yaml
type: PureMultipleChoiceExercise

xp: 50

key: d7bfc3b02f



```

After you calculate prevalence, the next step is interpreting it appropriately. Since prevalence is measured at a specific point in time in a specific population, choose an appropriate interpretation for the influenza prevalence of 0.02 in this sample of students.


`@hint`






`@possible_answers`
- The global risk of influenza is 2%.
- Students have a 2% chance of acquiring influenza each year.
- [In January 2018, 2% of students had influenza.]
- Students have a 0.02% chance of acquiring influenza each year.

`@feedbacks`
- Remember we cannot comment on the global disease burden based on a sample of students.
- Prevalence reflects current disease, whereas incidence refers to acquiring new disease.
- Right!
- We calculated a prevalence of 0.02, which means 2%.





---
## Prevalence practice

```yaml
type: NormalExercise

xp: 100

key: def437e2f4



```

Let's practice prevalence calculations. In this example, compare the prevalence of obesity in two countries. 

`@instructions`
In 2016, 330,000 adults lived in Iceland, and 78,000 were obese. 
In 2016, 1 billion adults lived in India, and 38 million were obese.
What was the adult prevalence of obesity in each country?

`@hint`


`@pre_exercise_code`
```{r}


```
`@sample_code`
```{r}
# Population in Iceland
population_Iceland <- 330000

# Cases of obesity in Iceland
cases_Iceland <- 

# Prevalence in Iceland

# Population in India
population_India <- 1*10^9

# Cases in India
cases_India <- 38*10^6

# Prevalence in India


```
`@solution`
```{r}
# Population in Iceland
population_Iceland <- 330000

# Cases of obesity in Iceland
cases_Iceland <- 78000

# Prevalence in Iceland
prevalence_Iceland <- cases_Iceland / population_Iceland

# Population in India
population_India <- 1*10^9

# Cases in India
cases_India <- 38*10^6

# Prevalence in India
prevalence_India <- cases_India / population_India

# Print the prevalence in Iceland
prevalence_Iceland

# Print the prevalence in India
prevalence_India
```





