
# higlass-data
Package that creates data files for CGAP's Higlass browsers

## Installation

Make sure `poetry` is installed on your system. Clone the repository and run `poetry install`

## Run a script

```
# -i input file path
# -o output file path
# -q Shows logs when set to False
poetry run create-cohort-vcf -i ./PATH/input.vcf -o ./PATH/input.multires.vcf -q False
the line i want to run:
poetry run create-cohort-vcf -i "C:\Users\thebe\Documents\test_data.chr1.vcf" -o "C:\Users\thebe\Documents\test_dataresults.chr1.vcf" -q False
```


