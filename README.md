# Scihub-Vector

Powered by scihub web3 community. Go to release page to download.

## What Is This?

We have vectorized the metadata from the paper stored in scihub. Currently, we include about 14,000,000+ paper which citation number is more than 3 times.

## What For?

It should be extremely useful when you like to search scihub paper using similarity match, or used for RAG and LLM model.

## How to use?

The file inside is format as JSON:

{

id

vector

text

}

They have been vectorized by nomic embedding with 768 dim. They can be used as input for vector database like Milvus.

## What’s Next?

We will continuedly making vectorized open science data, including metadata and full paper.
