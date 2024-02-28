# NLP Text summarization task

## Requirements

To run the IPython Notebook file (`roberta-pipelined.ipynb`), 
install dependencies from requirement.txt
## Running in Jupyter notebook 
Running in Jupyeter notebook, remove first 2 cells which deals with:
1. Mounting google drive collab.
2. changing drive path.

Others who are using google collab can continue with next steps.
## Finetuned Model and code

Download the finetuned Model (`Roberta_Classification_Model_Fine_Tuned`) and Code (understand the directory structure) from: 
https://drive.google.com/drive/u/0/folders/1a0xs2V2okCuznWO3bhkJztky2mI3bi50
upload and use your indian annual reports dataset folder instead of SourceData folder (with MDA reports).
Directory structure of reports folder(`SourceData`):


## Folder Structure Details

- **SourceData/** Contains folders of companies for which you want to generate the summaries 
    - **CompanySymbol/**: Contains company Annual_reports
        - **Annual_reports/**: Annual_reports contains MDA reports
            - CompanySymbol_year1_MDA.txt
            - CompanySymbol_year2_MDA.txt
    - **CompanySymbol2/**: Contains company Annual_reports
        - **Annual_reports/**: Annual_reports contains MDA reports
            - CompanySymbol2_year1_MDA.txt
            - CompanySymbol2_year2_MDA.txt
        

Update the variables  `curr_path` (only on google collab), and reports folder path `report_path` in the `roberta-pipelined.ipynb` and run all the cells to generate the summaries.
