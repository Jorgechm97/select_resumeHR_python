# Resume Keyword Searchcomi

This Python script is designed to search for specific keywords in resumes located in a directory and open the resumes that contain all the specified keywords. This can be useful for quickly filtering through a large set of resumes to find the most relevant ones based on specific criteria to the vacant positions.

## Setup: 1. Install the required libraries by running `pip install PyPDF2`.
2. Update the `keywords` list with the keywords you want to search for in resumes.
3. Download the resumes dataset from [Kaggle](https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset) or use your own set of resumes.
4. Update the `directory` variable with the path to the directory where the resumes dataset is located on your system.

## Functionality: The script performs the following actions: 1. **Text Normalization**: Normalizes the text in resumes for keyword matching by converting it to lowercase.
2. **Keyword Search**: Searches for the specified keywords in each summary and counts the occurrences of each keyword.
3. **Resume Opening**: Opens the resumes that contain all the keywords in the default web browser.
4. **Controlled Search**: Stops after opening 3 resumes that meet the keyword criteria.

## Usage: 1. Run the script in a Python environment.
2. The script will loop through all PDF files in the specified directory.
3. It will search for the keywords in each resume.
4. If a resume contains all the keywords, it will be opened in the default web browser.
5. The script will stop after opening 3 resumes that meet the keyword criteria.

## Important Notes: - The script uses PyPDF2 library for PDF parsing.
- Customize the list of keywords according to your specific requirements.
- Ensure that the directory path is correctly specified.
- Feel free to modify and enhance the script as needed.

## Contribution: - If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request on GitHub.

## Contact Information
- **LinkedIn:** [Jorge Chaves Montiel](https://www.linkedin.com/in/jorge-chaves-montiel/)

Happy resume searching! 📄🔍👀
