# LLM Zoomcamp 2026 — Homework 1: Agentic RAG

This repository contains my solution for **Homework 1: Agentic RAG** from the DataTalksClub LLM Zoomcamp 2026.

The homework focuses on building a Retrieval-Augmented Generation system from scratch and then extending it into an agentic RAG workflow.

## Overview

In this assignment, I worked with lesson markdown files from the LLM Zoomcamp GitHub repository as the knowledge base. The goal was to build a course teaching assistant that can answer questions using retrieved lesson content.

The main steps include:

* Loading course lesson files from GitHub using `gitsource`
* Parsing markdown lesson pages into documents
* Indexing documents with `minsearch`
* Building a basic RAG assistant
* Modifying the RAG helper class to work with `filename` and `content`
* Returning token usage from the OpenAI response
* Splitting long lesson pages into overlapping chunks
* Comparing token usage between full-document RAG and chunked RAG
* Creating a search function that can be used as a tool
* Building an agentic RAG flow where the model can call the search tool multiple times


## Key Concepts Practiced

* Retrieval-Augmented Generation
* Document indexing and keyword search
* Chunking long documents
* Prompt construction
* Token usage tracking
* Tool/function calling
* Agentic RAG loops



