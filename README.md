# Depression Risk Index

A data analytics capstone analyzing depression risk factors across a 
413,768-row dataset, with an interactive Power BI dashboard and a 
natural-language AI query tool built on top of it.

## Project Overview

This project explores what drives depression risk across demographic, 
socioeconomic, health, and lifestyle factors. It started as a Power 
BI dashboard and was extended with an AI-powered interface that lets 
users ask plain-English questions and get direct, data-grounded 
answers instead of manually clicking through filters.

## What's in this repo

- **Power BI dashboard** — explores risk across marital status, age, 
  employment, income, education, chronic illness, mental health 
  history (personal and family), substance abuse, diet, physical 
  activity, sleep, smoking, and parenthood.
- **Summary tables (CSV)** — 19 pre-aggregated tables, each breaking 
  down average risk score and sample size across one or two variables. 
  These power the AI query tool.
- **AI query app** — a natural-language interface (built with Lovable, 
  powered by Claude) that answers questions directly from the summary 
  tables, with a supporting statistic and chart, and clearly says when 
  a question falls outside what the data covers.
- **Case study** — write-up of the problem, approach, and key findings.

## Live app

https://clarity-chatbot.lovable.app

## Case study
[Read the full case study](Depression_Risk_Index_Case_Study.docx.pdf)

## Note on the raw dataset

The full raw dataset (413,768 rows) isn't included here due to 
GitHub's file size limits. 

## Tools used

Power BI, Lovable, Claude API
