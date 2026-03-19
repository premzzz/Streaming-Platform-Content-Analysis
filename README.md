Streaming Platform Content Analysis
A comparative data analysis project exploring the libraries of major streaming services: Netflix, Disney+, and Amazon Prime Video.

📌 Overview
This project analyzes and compares content distributions across multiple streaming platforms. Using Python and data visualization libraries, it examines the ratio of movies to TV shows, geographical production trends, and historical content growth to provide a cross-platform perspective on the streaming landscape.

🚀 Features
Cross-Platform Comparison: Aggregates data from Netflix, Disney+, and Amazon Prime Video into a unified dataset.

Content Distribution: Visualizes the breakdown of Movies vs. TV Shows for each provider.

Geographic Insights: Identifies leading content-producing countries (e.g., USA, India).

Trend Analysis: Tracks library growth and release year patterns.

Data-Driven Insights: Summarizes key takeaways regarding platform acquisition strategies and content types.

🛠️ Tech Stack
Language: Python

Libraries:

Pandas: Data manipulation and concatenation.

Matplotlib: Statistical data visualization.

Environment: Jupyter Notebook

📂 Project Structure
Plaintext
├── Data/
│   ├── netflix.csv       # Netflix content metadata
│   ├── disney.csv        # Disney+ content metadata
│   └── amazon.csv        # Amazon Prime Video metadata
├── cross_platform_report.ipynb  # Main analysis and visualization code
└── README.md             # Project documentation

📊 Key Findings
Dominant Format: Movies represent the primary content format across all platforms.

Library Scale: Netflix maintains a significantly larger library compared to its competitors, suggesting a more aggressive acquisition model.

Regional Leaders: The United States is the top content producer, followed by India.

Growth Trends: Netflix displays consistent growth in content releases over time.

Content Structure: While TV shows often feature multiple seasons, their total volume remains lower than standalone movies.

⚙️ Setup & Usage
Installation
Ensure Python 3.x is installed.

Install the necessary dependencies:

Bash
pip install pandas matplotlib
Running the Analysis
Place the datasets (netflix.csv, disney.csv, amazon.csv) inside a Data/ folder.

Open the Jupyter Notebook:

Bash
jupyter notebook cross_platform_report.ipynb
Execute the cells to generate the visualizations and report summary.
