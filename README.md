# Python_Control
The tool for reads trimming by required mean quality
## Arguments

-h (--help) - Show help message

-i (--input) - Input FASTQ file

-t (--threads) - Number of threads, default=1

-o (--output) - The resulting filename

-s (--start) - Number of cropped starting nucleotides

-e (--end) - Number of cropped nucleotides at the end of reads

-w (--window) - Sliding window

-q (--quality) - Required mean quality

  ## Usage example
  
`python Trimming.py -i /home/izmaylova/Downloads/test_classwork3.fastq -o /home/izmaylova/Downloads/test_classwork3_after_trimming.fastq -s 10 -e 5 -w 4 -q 30`
