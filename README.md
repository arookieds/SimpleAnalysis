# Simple Analysis

Desktop GUI application for quick exploratory data analysis of Excel files. Built to provide non-technical users with immediate statistical insights without requiring programming knowledge.

## Overview

A Python-based data analysis tool with graphical interface that enables users to load Excel files and instantly view statistical summaries and visualize variable relationships. Designed for accessibility - no coding required.

## Features

**Statistical Summary**
- Five-number summary (min, max, median, Q1, Q3)
- Mean calculations
- Automatic quantitative variable detection

**Data Visualization**
- Interactive variable selection
- Scatter plot generation for relationship analysis
- Visual exploration of correlations

**User Interface**
- File browser for Excel selection
- Automatic data loading and parsing
- Clear display of analytical results

## Tech Stack

- **Python** - Core application logic
- **Pandas** - Data manipulation and statistical calculations
- **GUI Framework** - User interface (specific framework in `user_interface.py`)
- **Excel Integration** - Direct .xlsx file reading

## Use Case

This tool bridges the gap between Excel users and programmatic analysis:
- Analysts needing quick statistical overviews
- Business users exploring data relationships
- Quality checks on quantitative datasets
- Rapid exploratory data analysis without scripting

## Project Structure

```
SimpleAnalysis/
├── data_analysis.py      # Core statistical computation logic
├── user_interface.py     # GUI implementation
└── icons/                # UI assets
```

## Status

**Functional Utility** - Working tool for specific use case

## Development Notes

Built as a practical solution to a real problem: providing accessible data analysis capabilities to users unfamiliar with Python or R. Demonstrates:
- User-centered design (GUI over CLI for target audience)
- Pandas data manipulation
- Statistical computation
- Practical problem-solving over technical complexity

---

**Note:** While simple in scope, this project reflects an important principle in data work - sometimes the best solution isn't the most technically sophisticated one, but the one that makes insights accessible to the people who need them.
