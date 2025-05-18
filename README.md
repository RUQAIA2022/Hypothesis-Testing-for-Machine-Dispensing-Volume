# Hypothesis-Testing-for-Machine-Dispensing-Volume
(a) State the null and alternative hypotheses
The null hypothesis (H₀) represents the status quo or the claim we're testing, while the alternative hypothesis (H₁) represents what we suspect might be true.

Null Hypothesis (H₀): The machine dispenses 80 mL on average.
H₀: μ = 80 mL

Alternative Hypothesis (H₁): The machine does not dispense 80 mL on average.
H₁: μ ≠ 80 mL

This is a two-tailed test because we're interested in deviations in either direction from 80 mL.

(b) Determine if there is enough evidence at 95% confidence level
We'll perform a z-test since we have a large sample size (n = 40 > 30) and know the sample standard deviation.

Given:

Sample mean (x̄) = 78 mL

Population mean (μ) = 80 mL (under H₀)

Sample standard deviation (s) = 2.5 mL

Sample size (n) = 40

Confidence level = 95% → α = 0.05

Step 1: Calculate the standard error (SE)
SE = s/√n = 2.5/√40 ≈ 0.3953

Step 2: Calculate the z-score
z = (x̄ - μ)/SE = (78 - 80)/0.3953 ≈ -5.06

Step 3: Determine the critical z-value for α = 0.05 (two-tailed)
The critical z-values are ±1.96

Step 4: Compare the test statistic to critical values
Our calculated z-score (-5.06) is more extreme than -1.96

Step 5: Calculate the p-value
For z = -5.06, the p-value is extremely small (much less than 0.0001)

Since the p-value < α (0.05) and |z| > 1.96, we reject the null hypothesis. There is sufficient evidence at the 95% confidence level to conclude that the machine is not dispensing 80 mL on average.
