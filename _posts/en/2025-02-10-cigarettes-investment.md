---
layout: post
title: "Cigarettes and Investment: How Smoking Quietly Destroys Your Wealth"
lang: en
categories: [en, blog]
tags: [finance, life, data]
---

We all know smoking is a terrible idea from a health perspective.  
A well-known study in the *British Medical Journal* estimates that **each cigarette shortens your life by about 11 minutes**, and on average, smokers live **6.5 years less** than non-smokers.

But beyond the health cost, there is a **massive financial cost** that people rarely quantify.  
In this article, I look at not only **how much smokers spend**, but also **how much they could have accumulated** if they had invested the same money in a simple index fund.

Spoiler: the gap after 30 years is staggering.

---

## How much does an average smoker consume?

Let’s consider an average French smoker. According to the [OFDT](https://www.ofdt.fr/statistiques-et-infographie/series-statistiques/tabac-evolution-de-lusage-occasionnel-ou-regulier-parmi-les-18-75-ans/), in 2018 a smoker consumed around:

- **13 cigarettes per day**

This number varies depending on gender and age, and the trend is decreasing.  
So the numbers below are conservative.

---

## Cigarette prices in France over the years

The price of cigarette packs in France has skyrocketed over the last 30 years, largely due to taxation.

I used historical pack prices available here:  
<https://github.com/Aunsiels/sp500_simulator/blob/main/data/cigarettes.json>

This gives us a realistic yearly cost of smoking over a 30-year horizon.

---

## The investment strategy: simple and realistic

Instead of spending money on cigarettes, imagine someone invested the same amount in the **S&P 500** — the simplest index fund you can buy.

Every time the smoker buys a pack, the non-smoker invests the equivalent amount.

This is an approximation:

- The price of a pack doesn’t buy a whole share → but DCA (small recurring contributions) is common
- We ignore taxes  
- We ignore fees  
- We assume the S&P 500 historical performance continues (which is reasonable over long horizons)

This is *not* a sophisticated finance model — just the simplest way to compare both behaviors.

---

## Results: smoking vs. investing

Below is the result of the simulation:  
- **Red** = money spent on cigarettes  
- **Blue** = money accumulated by investing the same amount in the S&P 500  

<iframe src="{{ '/assets/html/cigarettes.html' | relative_url }}"
        width="100%" height="525" style="border:none;"></iframe>

### After 30 years:

**The smoker:**  
- Spent **~40,000 €**  
- ≈ *2.5× the minimum annual wage*  
- ≈ *1.8× the median annual wage*  

**The non-smoker:**  
- Ends with **~105,000 €**  
- ≈ *6.5× the minimum annual wage*  
- ≈ *4.7× the median annual wage*

This is in spite of **four major recessions**:
- Dot-com crash  
- Subprime crisis  
- COVID-19 pandemic  
- War in Ukraine  

The compounding effect of long-term investing is incredibly powerful.

---

## Heavy smoker scenario

What if someone smokes a full pack per day (20 cigarettes)?

Then the equivalent investment becomes:

- **~163,000 €** after 30 years  
- ~*10× the minimum annual wage*

---

## A brutal conclusion

Smoking makes you:

- **live 6.5 years less**,  
- **work 6.5 years more**,  
- lose **tens of thousands of euros**,  
- and miss out on **six figures of potential wealth**.

That’s **13 years gone** — fewer lived, more worked.

If you can, replace cigarette spending with simple, regular investing.  
Compound interest is slow, then sudden — and always powerful.

The full code for the simulation is available here:  
<https://github.com/Aunsiels/sp500_simulator>

