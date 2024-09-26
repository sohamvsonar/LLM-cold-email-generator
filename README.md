# LLM Cold Email Generator

Overview
This project is designed to automate the process of scraping job listings, extracting relevant information from the scraped content, and generating personalized cold emails for outreach using LangChain. The pipeline uses a machine learning model, ChatGroq, and document loaders from LangChain to achieve these objectives.

Features:
Job Scraping: Scrape job listings from a specified website.
Information Extraction: Extract important details such as job role, experience, skills, and description using natural language models.
Portfolio Matching: Compare extracted job requirements to the user’s portfolio using a vector store for skill matching.
Cold Email Generation: Automatically generate cold emails tailored to the job description, highlighting relevant work in the portfolio.
