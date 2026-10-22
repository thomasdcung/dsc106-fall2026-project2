*This README is a template; replace the placeholders with your project details.*

# Project 2: Persuasive or Deceptive Visualization?

**Course:** DSC 106, Fall 2026, UC San Diego  
**Assignment:** [Project 2 instructions](https://dsc106.com/projects/project2/)

## Overview

This project explores how design choices shape what a reader concludes from data. Using a single dataset, we crafted two opposing visualizations, one arguing that a proposition is true and one arguing that it is not, and documented the design decisions behind each.

## Team

| Name | UCSD Email |
| --- | --- |
| *Thomas Cung* | *tdcung@ucsd.edu* |
| *Andrew Hoang* | *anh094@ucsd.edu* |
| *Xuan Yin* | *x9yin@ucsd.edu* |

## Dataset

- **Dataset:** *World Bank Data by Indicators 1960-2020*
- **Source:** *[link to the dataset](https://github.com/light-and-salt/World-Bank-Data-by-Indicators)*

## Proposition

> *Write the proposition here, e.g. "X increased after Y happened."*

## Visualizations

| Side | Description | File |
| --- | --- | --- |
| Proposition is **true** | *short description* | `vis_true.png` |
| Proposition is **not true** | *short description* | `vis_false.png` |

## Design Decisions and Reflection

For each visualization, the report lists 3-5 central design decisions, each scored from `-2` (fully deceptive) to `2` (fully earnest) with a short rationale. It ends with a 2-3 paragraph reflection on the overall process. See `index.html` for the full write-up.

## Project Structure

```
.
├── index.html        # Final report (based on the course HTML template)
├── vis_true.png      # Visualization supporting the proposition
├── vis_false.png     # Visualization opposing the proposition
├── data/             # Dataset files
├── notebooks/        # Exploratory analysis and plotting code
└── README.md
```

## don't touch anything below this
## --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Running Locally

1. Clone the repository:

   ```sh
   git clone <repo-url>
   cd <repo-name>
   ```

2. Open `index.html` in a browser, or serve it locally:

   ```sh
   python3 -m http.server 8000
   ```

   Then visit `http://localhost:8000`.

## Deployment

The report is deployed with GitHub Pages at: *[public URL here](https://thomasdcung.github.io/dsc106-fall2026-project2/)*

## Timeline

- **Checkpoint:** Wed 10/14, 11:59 PM (Gradescope PDF)
- **Final submission:** Wed 10/21, 11:59 PM (public HTML report)

## Acknowledgements

Assignment by the DSC 106 course staff (Instructor: Soohyun Nam Liao).
