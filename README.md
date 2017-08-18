# AAAI2018 PaperID 62

The paper investigates documentation of research for AI papers from AAAI-14, AAAI-16, IJCAI-13 and IJCAI-16.

## Paper selection
The sample populations for each conference was generated in the python script contained in the IPython notebook in `paper_selection.ipynb`. The population of accepted papers was collected in the files located under `data/accepted_papers_<conference>_<instalment>`. From these files, a random sample of 100 papers were selected for each, and stored in `data/sampled_<conference>_<instalment>`.

Note that for IJCAI-13, only the first 50 sampled papers were used during the survey, while 50 additional papers were revisited from previous work. These original 50 papers were chosen with the view of checking every paper from the conference, starting with the first listed paper from the Agent track.

## Analysis
A numerical summation of the evaluation is present in `evaluation_analysis.ipynb`, with calculations for the different degrees of reproducibility presented in the paper.

## Requirements
- Python version: 3.5.3
- See requirements.txt (with pip installed, run `pip install -r requirements.txt`)

## License

This project is free software. There is no warranty.

You may use, copy, modify and redistribute all files included in this project, subject to the terms and conditions of the [MIT license](https://opensource.org/licenses/MIT). See the file LICENSE-MIT.

In addition, you may use, copy, modify and redistribute all figures according to the terms and conditions of the [Create Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).