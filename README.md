# Automated Market Analyzer using Multi-Agent LLM

## Overview
This project leverages multiple language models (LLMs) to automate the process of analyzing competitors in the market. The system takes an input product query, searches for competitors using Google search, extracts relevant competitor information from web pages, and generates detailed competitor profiles. Using advanced LLMs, it analyzes these profiles, creates a comprehensive competitor analysis report, and saves the report as a PDF. The entire process is automated, helping businesses quickly assess market dynamics and competitor strategies.

## Features

*   **Competitor Discovery**: Automatically identifies competitors for a given product or service using Google’s Gemini API.
*   **Web Scraping**: Extracts detailed competitor information from web pages using Google Custom Search and BeautifulSoup.
*   **Competitor Information Extraction**: Uses advanced LLMs to analyze and extract relevant details from competitor data.
*   **Profile Generation**: Generates structured competitor profiles, including SWOT analysis and actionable insights.
*   **Automated Report Generation**: Compiles the competitor profiles into a detailed competitor analysis report.
*   **PDF Export**: Converts the competitor analysis report into a PDF file for easy sharing and presentation.

## Requirements

*   Google Custom Search API key
*   Google Cloud Project with Custom Search Engine (CX)
*   GPU support for running the LLMs (CUDA enabled)
