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
# Your
# sample
# code
# should
# be
# ideally
# 10 lines or less,
# with a max
# of 16 lines.
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




