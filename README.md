Campus Space Project
Purpose: Summarize how full a set of campus study spaces were when the were observed. The script reads one CSV file and reports total capacity, how many seats were in use, the overall occupancy rate, and which space was the most crowded relative to its size.

DATA
The records are synthetic teaching data. 
The tracked sample is the following:
data/sample/campus_spaces.csv

Repository Structure

campus-space-project/
-- README.md
-- .gitignore
-- scripts/             
-- data/sample/         
-- docs/                
-- outputs/             

'scripts/' houses the code that does the analysis
'data/sample/' houses the input data and is needed to reproduce the run.
'docs/' holds supporting documentation such as the data_dictionary.md
'outputs/' is where the generated results would go. 

Requirements
R 4.6.1 (tested with Rscript). No additional R packages are required.

How to Run
It is run from the repository root 'campus-space-project'

Rscript scripts/summarize_spaces.R data/sample/campus_spaces.csv

Expected Result

A successful run on the sample data prints the following:
'''
Rows: 12
Total seats: 278
Occupied seats: 214
Available seats: 64
Occupancy rate: 77.0%
Busiest observed space: S103
'''

Outputs

The script prints its summary to the terminal only. It does not create or modify any result file, so running it leaves 'outputs/' and the Git working tree unchanged. Yes.