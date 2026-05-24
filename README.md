# Intersectionality on Social Media

A project on hate speech and intersectionality on social media.

---

## What this is

This project looks at how minority women experience hate speech on social media differently from other groups. The starting point was a straightforward observation — intersectionality research suggests that people who belong to multiple marginalized groups face compounded forms of discrimination, not just additive ones. I wanted to see if that pattern shows up in social media data.

I used two publicly available datasets. The first helped me examine the prevalence of hate speech directed at different demographic groups. The second dataset, where the same content was labeled by everyday people rather than experts, let me look at differences in perception — whether people from different backgrounds interpret the same language as hateful or not.

To ground the quantitative findings in real experience, I also conducted short interviews with two people from minority communities in Bangladesh. Their accounts helped contextualize what the numbers were showing.

---

## What I found

Minority women receive disproportionately more hate speech than either minority men or majority women — not just more than one group, but more than both combined in many cases. This supports the intersectionality argument: the experience of a minority woman isn't just the sum of being a woman and being a minority, it's something compounded.

The perception analysis showed that people from different demographic backgrounds don't always agree on what counts as hate speech. The same content gets labeled differently depending on who's reading it, which has real implications for how AI moderation systems are trained and evaluated.

---

## Folder structure

```
notebooks/        data analysis and modeling
report/           final written report
results/          charts and output files
```

---

## How to run it

Install dependencies:

```bash
pip install -r requirements.txt
```

Then open the notebook in the `notebooks/` folder and run it top to bottom.

---

## Tools used

- Python — pandas, matplotlib, scikit-learn
- Jupyter Notebook
- Two publicly available hate speech datasets
