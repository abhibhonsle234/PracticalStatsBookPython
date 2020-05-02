# PracticalStatsBookPython
Hands on content from book by Peter Bruce and Andrew Bruce. Implemented with python and libraries, original is in R.

READ ME SOURCE - https://github.com/andrewgbruce/statistics-for-data-scientists

# Code associated with the book "Practical Statistics for Data Scientists: 50 Essential Concepts"

The scripts are stored by chapter and replicate most of the figures and code snippets.

HOW TO GET THE DATA: Run R script: The data is not saved on github and you will need to download the data. You can do this in R using the sript src/download_data.r. This will copy the data into the data directory ~/statistics-for-data-scientists/data.

Manual download: Alternatively, you can manually download the files from https://drive.google.com/drive/folders/0B98qpkK5EJemYnJ1ajA1ZVJwMzg or from https://www.dropbox.com/sh/clb5aiswr7ar0ci/AABBNwTcTNey2ipoSw_kH5gra?dl=0

IMPORTANT NOTE: The scripts all assume that you have cloned the repository into the top level home directory (~/) If you save the repository elsewhere, you will need to edit the line

PSDS_PATH <- file.path('~', 'statistics-for-data-scientists')

to point to the appropriate directory in all of the scripts.