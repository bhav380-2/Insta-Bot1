# Instagram Automation Notebook

This Jupyter Notebook automates various Instagram tasks using the Selenium library.

## Overview

The Instagram Automation Notebook performs the following tasks:

1. **Login to Instagram Handle:** Logs into an Instagram account.
2. **Search by Keyword:** Searches for a keyword on Instagram.
3. **Profile Interaction:**
    - Searches and opens a profile.
    - Follows/Unfollows any mentioned handle.

4. **Post Interaction:**
    - Likes/Unlikes top N posts of mentioned Instagram handle.

5. **Extract List of Followers:**
    - Extracts the first 500 followers of any specified account.
    - Prints followers you are following but who don't follow you.

6. **Story Checking:**
    - Checks the story of any Instagram handle.
    - Displays appropriate error messages for various scenarios.

## Usage

1. **Installation:**
    - Install the required dependencies:
        ```bash
        pip install selenium jupyter
        ```
    - Download the appropriate WebDriver (e.g., ChromeDriver) and set the path.
    - Open the notebook in Jupyter and run each cell.

2. **Setup:**
    - Update credentials and other necessary details within the notebook.

3. **Run the Notebook:**
    - Open the notebook in Jupyter.
    - Run each cell to execute the Instagram automation tasks.


## Acknowledgements

- This notebook utilizes the Selenium library for web automation.

## Contact Information

For any questions or support, please contact [Bhawesh Rathour](mailto:bhaweshrathour18@gmail.com).
