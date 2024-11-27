# `skore` - user testing

Thanks again for taking the time for this skore user test!

## Introduction

This repository serves as the template for a user interview about [skore](https://github.com/probabl-ai/skore), a new Python library that aims to enhance scikit-learn for data scientists.

This library is developped by the product team of [Probabl](https://probabl.ai/), the official brand operator of scikit-learn. More information about Probabl: [Notion page](https://rhinestone-nigella-aee.notion.site/Get-to-know-Probabl-1318cad47543801cb167f505e1be2b7a).

In this user test, a Probablr conducts an interview of a data science practitioner about skore, essentially to get some feedback. The interviewee does not need to look at skore before the actual meeting, as the goal is to get raw feedback such as:
- Is the documentation clear enough?
- Does the interviewee have a use case for such a product? How could Probabl improve skore to make it more useful for its use cases?

Is it ok to record this interview for internal (Probabl) usage?

## Agenda

In total, this user test should last less than 1 hour, to not take up too much of your time!

1. Presentation of Probabl and skore: ~5 min
1. Environment setup: ~5 min
1. User testing tasks: ~35 min
    - We prepared a template notebook on which to iterate: `compare_models.ipynb`.
1. Feedback Q&A: ~15 min

### Set-up: create your virtual environement

1. Clone this GitHub repository locally.
2. Create a virtual environment with your usual method (conda, virtualenv...), with `python>=3.9`.
3. Install the libraries in `requirements.txt` with:
```bash
pip install -r requirements.txt
```

### Goal of the user testing phase

- See `compare_models.ipynb`.
- We are using the californian housing dataset.
- The goal is to build a couple of models, and to compare them, using [skore](https://github.com/probabl-ai/skore) when it seems useful.
- [Skore's documentation](https://probabl-ai.github.io/skore/latest/index.html) can be helpful.

### Feedback Q&A

1. Overall experience
    - First impressions?
    - Pain points?
    - Unexpected discoveries?
2. Analysis flow
    - How natural was the storage/retrieval?
    - Dashboard creation experience?
    - What would improve your workflow?
3. Suggestions
    - Missing features?
    - Onboarding improvements?
    - Would you use skore in your day-to-day work?