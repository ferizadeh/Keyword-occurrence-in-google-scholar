
# Historic word occurrence in academic papers (Google SCholar)

## Summary 

This script extracts the historic word occurrence of a search term in
academic papers (from Google Scholar). It allows for spotting trends
in research and analyzing the relevance of a topic over time.


## Usage

`python extract_occurrences.py '<keyword>' <start date> <end date>` 

This command lists the number of publications for every year using
this keyword. The script just searches for articles and excludes
patents and citations.

## Example

- Search term: 'Explainbale AI'
- Desired time span: 2019 to 2024
- Command: `python extract_occurrences.py 'Explainbale AI' 2019 2024` 
- Output: `out.csv`, with the following contents:

| year | results |
|------|---------
| 2019 |    141  |
| 2020 |    292  |
| ...  |    ...  |	|
| 2024 |    2580 |

