# First-Year Marks Scatterplot

A Python data visualization project using `matplotlib` to analyze and plot the relationship between students' **Fieldwork Marks** and their **Overall Year Marks**.

The script parses student grade data from a CSV file and plots a customized scatter diagram annotated with standard UK university degree classification boundaries (1st, 2:1, 2:2, 3rd / Fail).

---

## 📌 Features

- **CSV Data Parsing:** Reads and extracts numerical grade pairs (`Field Mark` vs. `Overall Year`) from `first_year_marks.csv`.
- **Degree Classification Grid:** Custom axis ticks ($0\%, 40\%, 50\%, 60\%, 70\%, 100\%$) aligned with standard UK grade boundaries.
- **Visual Styling:** Blue 'X' data points with a customized green dashed background grid.

---

## 🛠️ Requirements

- Python 3.x
- `matplotlib`

Install dependencies using `pip`:

```bash
pip install matplotlib
