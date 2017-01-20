# Tesseract-CentOS

A compiled version of Tesseract (4.00.00alpha) for use within AWS Lambda functions.

1) `cd ~`
2) `git clone https://github.com/danielhomer/Tesseract-CentOS`
3) `cd ~/Tesseract-CentOS`
4) `LD_LIBRARY_PATH=~/Tesseract-CentOS/lib TESSDATA_PREFIX=~/Tesseract-CentOS ./tesseract`

