## BayerHackathon2024: Sensitivity and Uncertainty in Machine Learning Models
Event: BayerHackathon 2024
Theme: Data Science Meets Biology - Sensitivity and Uncertainty in Predictive Models
Team: Collaborative effort with five members (2 from Max Delbrück Center and 2 from 42 Berlin)

### Project Outline
This project highlights the potential of interdisciplinary approaches, combining molecular biology and data science, to improve the predictability and robustness of pharmaceutical models.  It explores the impact of point mutations in amino acid (AA) sequences on nanobody thermostability. By leveraging machine learning, we aim to analyze stability changes, validate model accuracy, and draw biochemically grounded insights into mutation effects.


1. Trained model used (TEMPRO model):
  - https://github.com/Jerome-Alvarez/TEMPRO/tree/main
	Goals:
	  - Understand model architecture and key components.
	  - Reproduce predictions on our dataset to establish baseline performance.
2. Data Mutation Pipeline:
  - Developed a custom function to introduce controlled point mutations into AA sequences, allowing:
	  - Selective replacement of amino acids.
	  - Structured examination of mutation impacts on model predictions.

3. Stability Analysis of Mutated Data:
  - Metrics:
	  - Range of Change: Predicted temperature variance.
	  - Mutation Positioning:
			Framework regions are hypothesized to impact stability more significantly than complementarity-determining regions (CDR).
	  - Mutation Depth: Quantify the number and type of AA mutations.
	  - Knowledge-based Adjustments:
			Amino acids with higher similarity should have a smaller impact on thermostability (Tm).
	  - Structural considerations:
		  - Focus on AA such as cysteine, known for structural integrity.
		  - 3D structural implications.

## Open Questions
Input Structure:

What forms the optimal input for stability prediction? (AA sequence, mutation types, 3D structure, and metadata).
Clarify whether point mutation data is the primary stability feature.
Model Extension & Benchmarking:

Extend and adapt existing models if compatible datasets are available.
Literature Review: Identify closely related studies, highlighting both similarities and differences.
Stability as a Metric: Define stability indicators specific to nanobody structural integrity.
Evaluating Prediction Confidence:

Develop criteria to assess the reliability of model predictions when inputs are altered.

# Bayer_2024
Bayer Meets Data Science 2024
