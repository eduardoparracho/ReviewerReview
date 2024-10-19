# ReviewerReview

This project aims to explore whether we can predict iPhone sales based on YouTube video statistics from review videos using the YouTube API. By analyzing various metrics like views, likes, comments, and engagement rates on iPhone review videos, the project seeks to find correlations or patterns that may offer insights into the predicted success of the product in the market.

Presentation available at https://docs.google.com/presentation/d/1-nc9yMFJckEq0Wdug668Ki0sOth_2bGYjqUuTpfegnk/edit?usp=sharing

## Project Overview

The goal of ReviewerReview is to leverage the YouTube Data API to gather review video metrics and analyze them to determine if there is a relationship between these metrics and iPhone sales figures. This could potentially assist in predicting how well a product, specifically an iPhone model, will sell based on feedback from tech reviewers and their viewers.

Key statistics considered include:

- View count
- Like ratio
- Comment ratio
- Previous Sales figures

By analyzing these data points, the project seeks to find if there is a predictable trend or correlation with actual iPhone sales data.

## Features

- Collects data from YouTube review videos of iPhone models.
- Analyzes video statistics.
- Compares video performance with real-world iPhone sales.
- Provides visualizations of trends and correlations.

## Installation

The repository has the follwoing dependencies:
- Requests, for API requests
- google_auth_oauthlib and googleapiclient, for specific Youtube API utilization
- Pandas, for DataFrame generation and manipulation
- Seaborn and MatPlotLib, for visualization

To use this project, you'll need access to the YouTube Data API. A new application will need to be registered in the Google API console - https://console.cloud.google.com/

## Future Work

- Expand the analysis to include other smartphone brands and products.
- Automate regular data fetching and analysis to provide real-time predictions.
- Use ChatGPT to analyse comment sections.

## Contributing

Contributions are welcome! If you have any ideas, bug fixes, or improvements, feel free to open an issue or submit a pull request.

- Fork the repository.
- Create your feature branch (git checkout -b feature/new-feature).
- Commit your changes (git commit -m 'Add some feature').
- Push to the branch (git push origin feature/new-feature).
- Open a pull request.


## Acknowledgements

Special thanks to Isidre Munne-Bertran, our teacher.

