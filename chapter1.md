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

This is the assignment text. It should help provide students with the background information needed.
The instructions that follow should be in bullet point form with clear guidance for what is expected.

`@instructions`
- Instruction 1
- Instruction 2
- Instruction 3
- Instruction 4

`@hint`
- Type this line: cases <- 100

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
success_msg("Nicely done! Measures of disease occurrence are the basis of all epidemiology.")
```






---
## Definitions

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



