# SMS Corpus Keyword Analysis

## Overview
This repository contains the solution for Assignment 1 of the CS4225 AY23/24 Semester 1. The assignment focuses on analyzing text message communication differences between Singaporeans and Americans using Hadoop Streaming and keyword analysis. The assignment involves performing keyword analysis on the NUS SMS Corpus, which consists of messages collected around 2011. The goal is to identify keywords used preferentially by Singaporean users compared to Americans.

## Key Points
- `mapper.py` : Python script for the mapper phase in Hadoop Streaming.
- `reducer.py` : Python script for the reducer phase in Hadoop Streaming.
- `stopwords.txt` : File containing stopwords to be ignored during keyword analysis.
- `sms.jsonl` : Large dataset file with 55,835 messages.
- `sms_small.jsonl` : Small dataset file with 5 messages (optional for debugging).
- `sample_output.txt` : Example of the correct output format.
- `output.txt` : My final output file.
