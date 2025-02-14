<div align="center">
  <picture>
    <source srcset="https://media.githubusercontent.com/media/probabl-ai/skore/main/sphinx/_static/images/Logo_Skore_Dark@2x.svg" media="(prefers-color-scheme: dark)">
    <img width="200" src="https://media.githubusercontent.com/media/probabl-ai/skore/main/sphinx/_static/images/Logo_Skore_Light@2x.svg" alt="skore logo">
  </picture>
</div>

# Take skore for a test drive!

## Intro

This repository is here to help you test and provide feedback on [skore](https://github.com/probabl-ai/skore), a new Python library that aims to enhance scikit-learn for data scientists.
skore is currently a work-in-progress, and more features are to be expected.

Skore is developed by the product team at [Probabl](https://probabl.ai/), a scikit-learn company. For more info, check us out: [Notion page](https://probabl.notion.site/Get-to-know-Probabl-127ef76d36b9804d8ca8e264e42f0cee).

## Agenda

In total, this test drive should last under an hour.

1. Presentation of Probabl and skore: ~5 min
1. Environment setup: ~5 min
1. User testing tasks: ~35 min
    - Here is a notebook to get you started: `estimator_report.ipynb` or `compare_models.ipynb`.
1. Feedback Q&A: ~15 min

### Set-up: create your virtual environment

1. Clone this GitHub repository locally.
1. Create a Python virtual environment with your usual method (conda, virtualenv...), with `python>=3.9`.
1. Install the libraries in `requirements.txt` with (activate your venv beforehand):
   ```bash
   pip install -r requirements.txt
   ```

If you did not follow these steps and just did `pip install -U skore`, please run:
```python
import skore; skore.show_versions()
```

### Goal of the test

The goal is to build a couple of models, and to compare them, using [skore](https://github.com/probabl-ai/skore) when relevant.

Resources:
- Notebook: `estimator_report.ipynb` or `compare_models.ipynb`
- [Skore documentation](https://skore.probabl.ai)

### Your feedback

Let us know what you think of skore!
Here are some topics on which we would appreciate your feedback:

1. Overall experience
    - First impressions?
    - Pain points?
    - Unexpected discoveries?
1. Analysis flow
    - How natural was the storage/retrieval?
    - Dashboard creation experience?
    - What would improve your workflow?
1. Suggestions
    - Missing features?
    - Onboarding improvements?
    - Would you use skore in your day-to-day work? Would you recommend skore to a colleague?

You can share your feedback:
- either directly by mail to the [Product Team](mailto:product-feedback@signal.probabl.ai),
- or on the `#skore` channel of our [Discord server](http://discord.probabl.ai).

## How to help?

- Give a star to the [skore repository](https://github.com/probabl-ai/skore)
- Tell your friends, invite them to test skore with this repo (https://github.com/probabl-ai/skore-user-test)
- Bring discussions to our [Discord server](http://discord.probabl.ai)
