## Project Overview
This project develops a restaurant recommendation and feedback analysis system using text mining and NLP techniques on restaurant reviews.

Main components:
- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Sentiment analysis
- Topic modeling (LDA)
- Feature engineering
- Predictive modeling for rating analysis
- Aspect-based interpretation for recommendation explanation

---

## Files
- `Project.ipynb` - main notebook containing the full pipeline
- `text_mining_final_report_ieee.pdf` - final report
- `requirements.txt` - package requirements

---

## Dataset

This project uses the Yelp Open Dataset.

### Download Link

https://www.yelp.com/dataset

---

### Required Files
Download the JSON files below:

- `yelp_academic_dataset_business.json`
- `yelp_academic_dataset_review.json`

---

### Folder Structure
After downloading, place the files in the following directory:

```text
project/
│── Project.ipynb
│── data/
│    ├── yelp_academic_dataset_business.json
│    └── yelp_academic_dataset_review.json
```

---

## How to Run

### 1. Create a Python environment
```bash
python -m venv venv
source venv/bin/activate
```

(Windows)

```bash
venv\Scripts\activate
```

---

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 3. Launch Jupyter

```bash
jupyter notebook
```

Open:

```text
Project.ipynb
```

and run all cells sequentially.

---

## Expected Output

The notebook produces:

* rating distribution plots
* review length analysis
* sentiment vs. rating correlation
* LDA topic summaries
* model evaluation metrics
* interpretable recommendation insights

