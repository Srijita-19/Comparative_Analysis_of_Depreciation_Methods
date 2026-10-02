# Comparative Analysis of Depreciation Methods Using Excel

## Straight-Line vs. Diminishing Balance

An Excel-based financial analysis project comparing the **Straight-Line** and **Diminishing Balance** methods of depreciation using a formula-driven 10-year depreciation model.

The project evaluates annual depreciation expense, depreciation rates, book-value movement, total depreciation, and the financial implications of different depreciation patterns.

## 📌 Project Overview

Depreciation is an important accounting and financial-analysis concept because the method selected affects the timing of expense recognition, reported profitability, and the carrying value of assets.

This project compares two depreciation methods:

* **Straight-Line Method**
* **Diminishing Balance Method**

Using the same asset assumptions, the project builds year-by-year depreciation schedules and evaluates how the two methods affect:

* Annual depreciation expense
* Book value of the asset
* Depreciation rate
* Total depreciation over the asset's useful life
* Timing of expense recognition
* Period-to-period financial reporting

The analysis was developed in Microsoft Excel using formula-driven calculations, structured schedules, comparative analysis, and visual presentation.

## 🎯 Business Problem

Businesses need to allocate the cost of fixed assets over their useful lives in a systematic manner.

However, different depreciation methods produce different patterns of expense recognition.

The key analytical question addressed in this project is:

**How does the choice between Straight-Line and Diminishing Balance depreciation affect annual expense recognition, asset book value, and financial reporting over an asset's useful life?**

The project therefore focuses not only on calculating depreciation, but also on understanding the **financial implications of the timing of depreciation expense**.

## 🎯 Objectives

The main objectives of the project are:

1. Calculate the total asset price after incorporating additional acquisition costs.
2. Calculate annual depreciation using the Straight-Line method.
3. Determine the annual Straight-Line depreciation percentage.
4. Calculate the Diminishing Balance depreciation rate.
5. Build 10-year depreciation schedules for both methods.
6. Compare annual depreciation expenses.
7. Compare year-by-year book values.
8. Calculate total depreciation over the asset's useful life.
9. Analyze the effect of depreciation timing on financial reporting.
10. Translate the numerical results into practical financial insights.

## 📊 Dataset / Input Assumptions

This project uses a structured set of asset assumptions rather than a large external dataset.

| Parameter              |    Value |
| ---------------------- | -------: |
| Asset Cost             |  450,000 |
| Additional Asset Cost  |   50,000 |
| Total Asset Price      |  500,000 |
| Scrap / Residual Value |   50,000 |
| Useful Life            | 10 Years |
| Depreciable Amount     |  450,000 |

The total asset price is calculated as:

**Asset Price = Asset Cost + Additional Asset Cost**

Therefore: 450,000 + 50,000 = 500,000

The depreciable amount is:

**Asset Price − Scrap Value**

500,000 − 50,000 = 450,000

# 🧮 Methodology

## 1. Straight-Line Method

The Straight-Line method allocates the depreciable amount equally across the asset's useful life.

**Formula**

Annual Depreciation = (Asset Price − Scrap Value) ÷ Useful Life

**Calculation**

Annual Depreciation = (500,000 − 50,000) ÷ 10 = 45,000 per year

### Straight-Line Depreciation Rate

Annual Depreciation ÷ Asset Price = 45,000 ÷ 500,000 = 9.00%

Therefore, the model recognizes 45,000 of depreciation every year.

## 2. Diminishing Balance Method

Under the Diminishing Balance method, depreciation is calculated as a fixed percentage of the asset's beginning book value.

Because the book value decreases every year, the absolute depreciation expense also decreases.

**Formula**

Depreciation = Beginning Book Value × Diminishing Balance Rate

The project calculates the rate as:

DB Rate = 1 − (Scrap Value ÷ Asset Price)^(1 ÷ Useful Life)

**Calculation**

DB Rate = 1 − (50,000 ÷ 500,000)^(1 ÷ 10) ≈ 20.5672%

This produces an accelerated depreciation pattern in which a larger amount of expense is recognized during the earlier years.

# 📈 Analysis Performed

**1. Asset Cost Analysis**

The project first determines:

* Initial asset cost
* Additional acquisition cost
* Total asset price
* Scrap value
* Depreciable amount
* Useful life

This establishes the base assumptions for both depreciation methods.

**2. Straight-Line Depreciation Analysis**

A 10-year schedule was created to calculate:

* Beginning book value
* Annual depreciation
* Ending book value

The annual depreciation remains constant at 45,000.

| Year | Beginning BV | Depreciation | Ending BV |
| ---: | -----------: | -----------: | --------: |
|    1 |      500,000 |       45,000 |   455,000 |
|    2 |      455,000 |       45,000 |   410,000 |
|    3 |      410,000 |       45,000 |   365,000 |
|    4 |      365,000 |       45,000 |   320,000 |
|    5 |      320,000 |       45,000 |   275,000 |
|    6 |      275,000 |       45,000 |   230,000 |
|    7 |      230,000 |       45,000 |   185,000 |
|    8 |      185,000 |       45,000 |   140,000 |
|    9 |      140,000 |       45,000 |    95,000 |
|   10 |       95,000 |       45,000 |    50,000 |

**3. Diminishing Balance Analysis**

The project also creates a 10-year Diminishing Balance schedule.

| Year | Beginning BV | Depreciation |  Ending BV |
| ---: | -----------: | -----------: | ---------: |
|    1 |   500,000.00 |   102,835.88 | 397,164.12 |
|    2 |   397,164.12 |    81,685.45 | 315,478.67 |
|    3 |   315,478.67 |    64,885.06 | 250,593.62 |
|    4 |   250,593.62 |    51,540.03 | 199,053.59 |
|    5 |   199,053.59 |    40,939.70 | 158,113.88 |
|    6 |   158,113.88 |    32,519.56 | 125,594.32 |
|    7 |   125,594.32 |    25,831.21 |  99,763.12 |
|    8 |    99,763.12 |    20,518.46 |  79,244.66 |
|    9 |    79,244.66 |    16,298.39 |  62,946.27 |
|   10 |    62,946.27 |    12,946.27 |  50,000.00 |

# 🔍 Comparative Analysis

| Metric                   | Straight-Line | Diminishing Balance |
| ------------------------ | ------------: | ------------------: |
| Annual Pattern           |      Constant |           Declining |
| Depreciation Rate        |         9.00% |            20.5672% |
| Year 1 Depreciation      |     45,000.00 |          102,835.88 |
| Year 2 Depreciation      |     45,000.00 |           81,685.45 |
| Year 4 Ending Book Value |    320,000.00 |          199,053.59 |
| Total Depreciation       |    450,000.00 |          450,000.00 |
| Final Book Value         |     50,000.00 |           50,000.00 |

---

# 📌 Key Findings / Results

**1. Straight-Line produces a constant expense**

The Straight-Line method recognizes 45,000 of depreciation every year.

This creates a predictable and stable annual expense pattern.

**2. Diminishing Balance accelerates early depreciation**

The Diminishing Balance method recognizes:

* **102,835.88** depreciation in Year 1
* **81,685.45** in Year 2
* **51,540.03** in Year 4
* **12,946.27** in Year 10

Therefore, the depreciation expense is significantly higher during the early years and progressively declines.

**3. Year 1 difference is significant**

Year 1 depreciation:

Straight-Line = 45,000.00
Diminishing Balance = 102,835.88

The Diminishing Balance method therefore recognizes substantially more expense in the first year under the project's assumptions.

**4. Book value declines faster under Diminishing Balance**

At the end of Year 4:

Straight-Line Book Value = 320,000.00
Diminishing Balance Book Value = 199,053.59

The lower book value under Diminishing Balance results from the accelerated recognition of depreciation during earlier years.

**5. Total depreciation is the same**

Both methods ultimately recognize:

Total Depreciation = 450,000

and both reach:

Final Book Value = 50,000

Therefore, under the assumptions used in this model, the primary difference between the methods is **the timing and pattern of expense recognition**, rather than the total depreciable amount.

# 💼 Business Insights

**Straight-Line Method**

Straight-Line depreciation may provide a useful approach when an asset is expected to provide relatively consistent economic benefits throughout its useful life.

Key characteristics:

* Predictable annual expense
* Simple calculation
* Stable impact on annual profit
* Easier budgeting and forecasting
* Consistent reduction in book value

**Diminishing Balance Method**

Diminishing Balance may be more appropriate for assets where economic usefulness or value declines more rapidly during the early years.

Key characteristics:

* Higher early-year depreciation
* Lower later-year depreciation
* Faster reduction in carrying value
* More closely reflects an accelerated consumption pattern for certain assets

# 📊 Financial Reporting Implications

The depreciation method does not change the total depreciable amount in this model, but it changes **when the expense is recognized**.

All else equal:

**Straight-Line**

Produces a relatively stable annual depreciation expense.

**Diminishing Balance**

Produces: **Higher expense → earlier years**

followed by: **Lower expense → later years**

Consequently, the method selected can affect period-to-period:

* Depreciation expense
* Reported profit
* Asset carrying value
* Financial performance trends

The actual accounting or tax treatment must be determined using the applicable accounting standards, tax regulations, and company policies.

# 🧠 Advanced Analysis

The project addresses several advanced financial-analysis questions, including:

| Question                                |     Result |
| --------------------------------------- | ---------: |
| Annual Straight-Line depreciation       |  45,000.00 |
| Total Straight-Line depreciation        | 450,000.00 |
| Straight-Line ending book value         |  50,000.00 |
| Diminishing Balance rate                |   20.5672% |
| Diminishing Balance Year 2 depreciation |  81,685.45 |
| Diminishing Balance Year 4 ending BV    | 199,053.59 |
| Total Diminishing Balance depreciation  | 450,000.00 |
| Diminishing Balance ending book value   |  50,000.00 |
| Difference in total depreciation        |       0.00 |

# ⚠️ Limitations

This is an educational financial-analysis model based on the assumptions provided in the project.

The model does not incorporate:

* Tax-specific depreciation rules
* Component depreciation
* Impairment
* Revaluation
* Partial-year depreciation conventions
* Disposal proceeds
* Changes in useful-life estimates
* Changes in residual-value estimates
* Jurisdiction-specific accounting requirements

The Diminishing Balance schedule is calibrated to reach the specified scrap value of **50,000** at the end of Year 10.

# 📌 Conclusion

The analysis demonstrates that Straight-Line and Diminishing Balance depreciation can produce the same total depreciation over an asset's useful life when the same asset price and residual value are used.

The major difference is the timing of expense recognition.

Straight-Line recognizes 45,000 consistently each year, while Diminishing Balance recognizes a significantly higher depreciation expense in the early years and progressively lower amounts later.

For the assumptions used in this project:

* Asset Price = 500,000
* Scrap Value = 50,000
* Useful Life = 10 years
* Straight-Line Depreciation = 45,000/year
* Straight-Line Rate = 9.00%
* Diminishing Balance Rate = 20.5672%
* Total Depreciation under both methods = 450,000
* Final Book Value under both methods = 50,000

The project demonstrates how accounting assumptions can influence the **timing of expenses, reported profitability, and asset carrying values**, making depreciation-method analysis relevant to financial reporting, budgeting, forecasting, and financial decision-making.
