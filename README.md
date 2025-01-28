# Real-Time Word Co-Occurrence Analysis

1. A PySpark development setup is being prepared, incorporating essential elements such as SparkConf, SparkContext, and
StreamingContext.

2. Our focus is on building a program that analyzes word pairs in streaming text data.

3. Using two execution threads and a batch interval of one second, we're establishing a local StreamingContext.

4. Netcat is being utilized to create a DStream that represents data flowing from a TCP source (localhost:9999).

5. Functions for text processing are under development, aimed at word separation, lowercase conversion, and punctuation
elimination.

6. From the cleaned word list, we're crafting a method to generate bigrams.

7. The data stream undergoes a sliding window transformation, with a three-second window length and a two-second sliding
interval.

8. Within these sliding windows, we're tallying and displaying the frequency of each bigram.

9. We're evaluating how our selected window size and sliding interval affect the bigram analysis.

10. Comprehensive logs of the processed information are being generated in both JSON and plain text formats.

11. Result analysis and visualization are underway, encompassing sentence counts per window, ongoing averages, and trend
patterns.

This project is designed to provide practical experience in processing data in real-time, understanding distributed computing
principles, and applying text analysis methods in a streaming environment.
