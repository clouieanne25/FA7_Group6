# FA 7 - Campus-Related Statistical Analysis

## Group
**Folder:** `FA7_GroupNumber`

## Topics
- **Part 1 (Exponential Distribution):** Time intervals between students entering a campus restroom.
- **Part 2 (Normal Distribution):** Weight of students' backpacks.

---

# Part 1 - Exponential Distribution

### Scenario
We recorded the arrival time of 31 students entering a campus restroom. The 30 intervals between consecutive arrivals were analyzed.

### Method
For each consecutive pair of students:
`interval = next arrival time - previous arrival time`

The exponential model uses:
- Mean waiting time: `E(X) = 1/λ`
- PDF: `f(x) = λe^(-λx), x >= 0`
- CDF: `P(X <= x) = 1 - e^(-λx)`

### Results
- Number of intervals: **30**
- Mean interval: **1.4683 minutes**
- Mean interval: **88.10 seconds**
- Estimated rate λ: **0.6810 per minute**

Selected probabilities:
- P(X ≤ 1 minute) = **49.39%**
- P(X ≤ 2 minutes) = **74.39%**
- P(X ≤ 3 minutes) = **87.04%**
- P(X > 5 minutes) = **3.32%**

### Interpretation
The estimated average gap between restroom entries is about **1.47 minutes**. Under the exponential model, short gaps are more common and the probability decreases as the waiting time becomes longer. The model is useful for estimating how likely another student is to enter within a given time.

### Limitations
The observation was made over one short period and may not represent the whole school day. Restroom traffic can change by class schedule, break time, and location. The exponential model is an approximation and assumes events occur randomly and independently at a roughly constant average rate.

---

# Part 2 - Normal Distribution

### Scenario
The class collected **50 backpack-weight responses** in kilograms through Google Forms.

### Results
- Sample size: **50**
- Mean (μ): **3.17 kg**
- Sample standard deviation (σ): **0.98 kg**
- Minimum: **1.0 kg**
- Maximum: **5.2 kg**
- Median: **3.00 kg**

Observed percentages within the sample mean ± kσ:
- Within 1σ: **66.00%**
- Within 2σ: **94.00%**
- Within 3σ: **100.00%**

### Interpretation
Most backpack weights are concentrated around the middle of the observed range, with the largest frequency at approximately 3.0 kg. The data are reasonably centered but are not a perfect normal distribution because several values occur only once or twice. The distribution has a moderate spread, so students carry noticeably different amounts of material.

### Real-life implications
Students and teachers can use the results to discuss whether backpacks are becoming unnecessarily heavy. The school could encourage students to bring only materials needed for the day, use digital copies when appropriate, and provide storage options when available.

### Important data note
The Part 2 values in this package were transcribed from the frequency chart shown in the provided screenshot (50 responses). If the original Google Forms response spreadsheet is available, replace `Part2_Normal/data.csv` with the exact exported raw responses before final submission.

---

# Presentation / Defense Talking Points

1. **Why did you choose the restroom-entry interval?**
   We chose it because it is a measurable campus event where the time between consecutive arrivals can be modeled using an exponential distribution.

2. **Why exponential distribution?**
   It is appropriate for modeling waiting times between events that are assumed to occur randomly and independently at an approximately constant average rate.

3. **What is λ?**
   Lambda is the estimated rate of occurrence per minute. Here, λ is the reciprocal of the mean interval.

4. **What is the main Part 1 finding?**
   The average interval is about **1.47 minutes**, so a student enters approximately once every **1.47 minutes** during the observation period.

5. **What is the main Part 2 finding?**
   The average backpack weight is about **3.17 kg**, with a sample standard deviation of **0.98 kg**.

6. **Are the data perfectly normal?**
   No. A normal curve is a useful approximation, but real campus data do not have to fit it perfectly.

7. **What are the limitations?**
   The samples were collected during limited periods and may not represent every time of day or every student on campus.

8. **What is the real-life use?**
   The results can help understand restroom traffic and student backpack loads and can support practical scheduling or student-wellness recommendations.

