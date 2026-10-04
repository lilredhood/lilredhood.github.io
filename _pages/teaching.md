---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 2
---

## Practical sessions

> **How to use the notebooks**
>
> First download the notebook using the **Download notebook** link below.
> Then open [Google Colab](https://colab.research.google.com/), choose **Upload**, and select the downloaded `.ipynb` file.
>
> The direct **Open in Colab** link may also work, but downloading the notebook first is the recommended method.


### TP1 — Battery Time Series & Electrical Modelling

Exploration of battery time series, state-of-charge dynamics, and identification of a simple equivalent-circuit electrical model.

[Download notebook](/assets/notebooks/TP1_battery_time_series_JAX.ipynb)

[Open in Colab](https://colab.research.google.com/github/lilredhood/lilredhood.github.io/blob/main/assets/notebooks/TP1_battery_time_series_JAX.ipynb)


### TP2 — Battery Ageing with Neural ODEs

Introduction to hybrid modelling of battery ageing with Neural ODEs.

Starting from a calibrated electrical model, the ageing dynamics of capacity and internal resistance are learned from synthetic vehicle time series. The model is then extended from a single vehicle to a fleet, with an introduction to history-dependent ageing and memory effects.

[Download notebook](/assets/notebooks/TP2_neural_ode_battery_ageing.ipynb)

[Open in Colab](https://colab.research.google.com/github/lilredhood/lilredhood.github.io/blob/main/assets/notebooks/TP2_neural_ode_battery_ageing.ipynb)


### TP3 — Discovering Ageing Laws with SINDy

Extraction of interpretable ageing laws from a previously trained Neural ODE.

The learned continuous dynamics are sampled and analysed using sparse regression and SINDy in order to recover compact symbolic equations describing capacity fade and resistance growth.

[Download notebook](/assets/notebooks/TP3_sindy_neural_ode.ipynb)

[Open in Colab](https://colab.research.google.com/github/lilredhood/lilredhood.github.io/blob/main/assets/notebooks/TP3_sindy_neural_ode.ipynb)
