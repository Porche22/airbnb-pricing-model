# Airbnb Pricing Model

> **Category:** Machine Learning &nbsp;·&nbsp; **Type:** Jupyter notebook project

## Overview

Airbnb is an online platform that allows people to rent short-term accommodation. This ranges from regular people with a spare bedroom to property management firms who lease multiple rentals. On the one side, Airbnb enables owners to list their space and earn rental money. On the other side, it provides travelers easy access to renting private homes.

Airbnb receives commissions from two sources upon every booking, namely from the hosts and guests. For every booking, Airbnb charges the guest 6-12% of the booking fee. Moreover, Airbnb charges the host 3% for every successful transaction.

As a senior data scientist at Airbnb, you have to come up with a pricing model that can effectively predict the Rent for accommodation and can help hosts, travelers, and also the business in devising profitable strategies.

To explore and visualize the data, build a linear regression model to predict the prices of Airbnb rental rooms, and generate a set of insights and recommendations that will help the business.

* id: Property ID
  * room_type: Type of Room in the property
  * accommodates: How many adults can this property accommodate
  * bathrooms: Number of bathrooms on the property
  * cancellation_policy: Cancellation policy of the property
  * cleaning_fee: This denotes whether the property cleaning fee is included in the rent or not
  * instant_bookable: It indicates whether an instant booking facility is available or not
  * review_scores_rating: Review rating score of the property
  * bedrooms: Number of bedrooms in the property
  * beds: Total number of beds in the property
  * log_price: Log of the rental price of the property for a fixed period.

## Project deep dive

This repository contains a complete, end-to-end notebook for **Airbnb Pricing Model**.
It walks through the full workflow — from framing the problem and exploring the
data, through modeling and evaluation, to the conclusions and recommendations.

- **11 code steps** of analysis and modeling
- Full outputs, tables, and visualizations preserved in the rendered HTML
- A runnable `notebook.ipynb` so you can re-execute and extend the work

## Tech stack

`matplotlib`, `numpy`, `pandas`, `scikit-learn`, `seaborn`

## What's in this repo

| File | Description |
|------|-------------|
| [`notebook.ipynb`](notebook.ipynb) | The runnable notebook (code recovered from the original export) |
| [`airbnb-pricing-model.html`](airbnb-pricing-model.html) | Full rendered notebook with **all outputs & plots** preserved |
| `requirements.txt` | Python dependencies inferred from the notebook |

## View the notebook

GitHub renders `.ipynb` files inline — just open [`notebook.ipynb`](notebook.ipynb).
For the fully-rendered version with every saved output and figure:

- **Rendered notebook (nbviewer):** https://nbviewer.org/github/Porche22/airbnb-pricing-model/blob/main/notebook.ipynb
- **Rendered HTML export:** https://htmlpreview.github.io/?https://github.com/Porche22/airbnb-pricing-model/blob/main/airbnb-pricing-model.html

> Replace `Porche22` with your GitHub username after pushing.

## Run it locally

```bash
git clone https://github.com/Porche22/airbnb-pricing-model.git
cd airbnb-pricing-model
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```

---

<sub>Notebook reconstructed from an nbconvert HTML export; code cells recovered
faithfully, rich outputs are preserved in the accompanying `.html`.</sub>
