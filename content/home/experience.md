+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Machine Learning Intern"
  company = "PepsiCo"
  company_url = ""
  location = "New York, NY, USA"
  date_start = "2020-06-29"
  date_end = "2020-08-07"
  description = """
  - Trained a Word2Vec-like model on customer product baskets to create a low-dimensional embedding space of these products (using TensorFlow).
  - Implemented the measures of “complementarity” and “substitutability” between different products under the representation learning paradigm, inspired by the paper - [Product2Vec](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3519358).
  - Used techniques like t-SNE to visualize the manifold and qualitatively validate that a pair of products that are complementary or substitutes must be close in the embedding space.
  """

[[experience]]
  title = "Data Science Intern"
  company = "Noodle.ai"
  company_url = ""
  location = "Bengaluru, India"
  date_start = "2019-01-07"
  date_end = "2019-05-03"
  description = """
  - Designed the pipeline that was internally used by the data science team for pre-processing and structuring different time-series datasets for problems like forecasting and anomaly detection.
  - Developed a modular and reusable python framework (called “sequel”) for working with sequence-to-sequence models in Keras.
  - Designed a benchmark suite for evaluating different sequence-to-sequence architectures for multivariate time series forecasting (on internal datasets of the company).
  """

[[experience]]
  title = "Data Science Intern"
  company = "Noodle.ai"
  company_url = ""
  location = "Bengaluru, India"
  date_start = "2018-05-21"
  date_end = "2018-06-22"
  description = """
  - Worked on a system to estimate the time required by an order (of steel coils) to get ready. Performed exploratory data analysis on the client’s data with the aim to understand the manufacturing process and model it.
  - Further, created an auxiliary conditional probabilistic model for a specific scenario in the manufacturing process. When integrated into the existing system, this model could improve the results by ~20%.
  - Made extensive use of `Python` (along with various open-source libraries including, but not limited to `Pandas`, `NumPy`, `Scikit-learn` and `Plotly`) for data pre-processing, modeling and data visualization.
  """

# [[experience]]
#   title = "Data Science Intern"
#   company = "Noodle.ai"
#   company_url = ""
#   location = "Bengaluru, India"
#   date_start = "2017-06-12"
#   date_end = "2017-07-14"
#   description = """
#   - Developed a tool (python package) to extract the data from the [Global Database of Events, Language, and Tone (GDELT)](https://www.gdeltproject.org/) - manually, or via Google’s BigQuery. Also, created wrapper functions for pre-processing of the data collected. 
#   - GDELT was to be used as an external data source, providing additional data related to the problem domain. The utility was called `gydelt` and can be viewed [here](https://mrinaljain17.github.io/gydelt/).
#   """

+++
