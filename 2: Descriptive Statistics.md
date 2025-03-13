# Lesson 2: Descriptive Statistics

## 1️⃣ What is Descriptive Statistics?

Descriptive Statistics is the process of summarizing and organizing data in a meaningful way. It helps us understand patterns, trends, and key characteristics of data.

### Example

🏫 Imagine you have test scores of students in a math class:
📊 [75, 80, 92, 88, 95, 79, 85, 90, 93, 78]

Instead of analyzing each number individually, we can use Descriptive Statistics to find:

- Mean (Average) score
- Median (Middle Value)
- Mode (Most common score)
- Range (Difference between highest and lowest scores)

## 2️⃣ Measures of Central Tendency (Mean, Median, Mode)

These measures describe where the center of the data lies.

### (a) Mean (Average)

The mean is the sum of all values divided by the number of values:

Mean = ∑X / N

🔹 **Example**:
Math scores: [75, 80, 92, 88, 95, 79, 85, 90, 93, 78]

Mean = (75+80+92+88+95+79+85+90+93+78) / 10 = 85.5

📌 **Interpretation**: The average score is 85.5.

### (b) Median (Middle Value)

The median is the middle value when the data is arranged in ascending order.

🔹 **Example**:
Sorted scores: [75, 78, 79, 80, 85, 88, 90, 92, 93, 95]

Since we have 10 values (even number), the median is the average of the 5th and 6th values:

(85+88) / 2 = 86.5

📌 **Interpretation**: The middle score is 86.5.

### (c) Mode (Most Frequent Value)

The mode is the most frequently occurring value in a dataset.

🔹 **Example**:
Scores: [75, 80, 92, 88, 95, 79, 85, 90, 93, 78]

📌 Since no value repeats, there is no mode.

📌 If the scores were [75, 80, 92, 88, 95, 79, 85, 90, 93, 85], the mode would be 85 because it appears twice.

## 3️⃣ Measures of Dispersion (Spread of Data)

These measures tell us how spread out the data is.

### (a) Range

Range = Highest value - Lowest value

🔹 **Example**:
Scores: [75, 80, 92, 88, 95, 79, 85, 90, 93, 78]

Range = 95 - 75 = 20

📌 **Interpretation**: The scores vary by 20 points.

### (b) Variance (σ²)

Variance measures how far each value is from the mean.

σ² = ∑(X-X̄)² / N

🔹 **Example Calculation (Simplified)**:
For the scores [75, 80, 92, 88, 95, 79, 85, 90, 93, 78],
1️⃣ Find Mean: 85.5
2️⃣ Subtract each score from the mean and square the result
3️⃣ Take the average of these squared values

| Score | Deviation from Mean | Squared Deviation |
|-------|---------------------|-------------------|
| 75    | -10.5               | 110.25            |
| 80    | -5.5                | 30.25             |
| 92    | 6.5                 | 42.25             |
| 88    | 2.5                 | 6.25              |
| 95    | 9.5                 | 90.25             |
| 79    | -6.5                | 42.25             |
| 85    | -0.5                | 0.25              |
| 90    | 4.5                 | 20.25             |
| 93    | 7.5                 | 56.25             |
| 78    | -7.5                | 56.25             |
| **Total** | | **454.5** |

Variance = 454.5 / 10 = 45.45

📌 Variance ≈ 45.45

### (c) Standard Deviation (σ)

The Standard Deviation is the square root of the variance:

σ = √σ²

🔹 **Example**:

σ = √45.45 ≈ 6.74

📌 **Interpretation**: Most students' scores are within ±6.74 points of the mean (85.5).

## 4️⃣ Skewness and Kurtosis

These measure the shape of the data distribution.

### (a) Skewness (Symmetry of Data)

- **Positive Skew (Right-Skewed)** → Tail is on the right (e.g., salaries).
- **Negative Skew (Left-Skewed)** → Tail is on the left (e.g., exam scores where most students score high).

```
Positive Skew:  Low [------|------] High
                        ^
                       Mean
                      Median

Negative Skew: Low [------|------] High
                          ^
                         Mean
                        Median

Normal (Symmetric): Low [------|------] High
                              ^
                          Mean = Median
```

🔹 **Example**: If a test is too easy, most students score high, and the data is left-skewed.

### (b) Kurtosis (Peakedness of Data)

- **High Kurtosis** → Tall and sharp peak (less variation).
- **Low Kurtosis** → Flat distribution (more variation).

```
High Kurtosis:    /\
                 /  \
               _/    \_

Normal Kurtosis:  /\
                 /  \
               _/    \_

Low Kurtosis:     /\
                _/  \_
```

🔹 **Example**: If every student scores between 80 and 90, the kurtosis is high (less spread).

## 5️⃣ Visualization of Descriptive Statistics

📊 Histograms & Boxplots help visualize data.

### Example Histogram of Test Scores

A histogram of math scores can show how frequently each score range appears.

| Score Range | Frequency |
|-------------|-----------|
| 70-79       | 3         |
| 80-89       | 4         |
| 90-100      | 3         |

```
Frequency
4 |          ####
3 |    ####  ####  ####
2 |    ####  ####  ####
1 |    ####  ####  ####
0 +------------------------
     70-79  80-89  90-100
       Score Ranges
```

📌 **Interpretation**: Most students scored between 80 and 89.

### Example Boxplot of Test Scores

A boxplot shows the distribution of scores including quartiles and outliers.

```
75         79    86.5  92       95
|----------|------|-----|-------|
Min        Q1    Med   Q3      Max
```

## 6️⃣ Real-World Applications

🎯 **Machine Learning**: Helps in feature scaling and understanding data distributions.

🎯 **Medical Studies**: Used to analyze patient health statistics.

🎯 **Business Analytics**: Helps in understanding sales trends and customer behavior.

## 7️⃣ Quick Recap 📝

✅ **Mean, Median, Mode** → Find the center of data.

✅ **Range, Variance, Standard Deviation** → Measure how spread out data is.

✅ **Skewness & Kurtosis** → Understand data shape.

✅ **Histograms & Boxplots** → Help visualize statistics.

This lesson covers Descriptive Statistics in an easy-to-understand way!
