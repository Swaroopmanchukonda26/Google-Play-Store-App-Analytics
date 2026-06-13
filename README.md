# Google Play Store Mobile App Analytics Dashboard

An interactive exploratory data data science project analyzing over 8,000 mobile apps from the Google Play Store storefront to isolate category saturation, user installations, and pricing optimization benchmarks using Pandas and Plotly Express.

## 🚀 Key Architectural Discoveries
* **Market Satiation:** Family and Game genres dominate the store in raw app counts, but Tools and Games lead by hundreds of millions in total downloads.
* **The Cost of Pricing:** Notched statistical box plots reveal that transitioning from a Free model to a Paid model can result in a 100x reduction in median user downloads.
* **Premium Category Niches:** While the storewide pricing median sits at $2.99, consumers display a significantly higher price tolerance in highly specialized niches like Medical ($5.49) and Dating ($6.99).

## 🛠️ Data Science Toolkit Used
* **Languages & Environments:** Python, Google Colab
* **Libraries:** Pandas, Plotly Express (`px.pie`, `px.bar`, `px.scatter`, `px.box`)
* **Core Mechanisms:** Subset Deduplication (`.drop_duplicates()`), Advanced String Scrubbing, Feature Engineering, Multi-Dataframe Merging (`pd.merge()`), Multi-Dimensional Logarithmic Bubble Mapping, and NLP Multi-Genre Unstacking (`.str.split().stack()`).
