
# Analysis of Organizations Mentioned in News from the First Quarter of 2015

This project analyzes the organizations mentioned in news articles in the "Market" category during the first quarter of 2015. We use the monilouise/ner_pt_br model for named entity recognition (NER) to identify organizations mentioned in the texts. We then generate a ranking of the most mentioned organizations and visualize the data in a horizontal bar chart and a word cloud using the NLTK stopword list.

## Data

The data used in this project is available on Kaggle. You can access it through the following link:
[https://www.kaggle.com/datasets/marlesson/news-of-the-site-folhauol](https://www.kaggle.com/datasets/marlesson/news-of-the-site-folhauol)

## Dependencies

Make sure to install the following libraries before running the code:

- pandas
- transformers
- torch
- nltk
- matplotlib
- tqdm
- wordcloud
- seaborn

You can install the dependencies by running:

```bash
pip install pandas transformers torch seaborn matplotlib tqdm wordcloud
```

## Running Docker in VS Code

To set up and run the project using Docker in VS Code, follow these steps:

### Step 1: Install Docker

Download and install Docker from the [Docker Desktop](https://www.docker.com/products/docker-desktop/) link.

### Step 2: Install Docker Extension in VS Code

Install the Docker extension in VS Code to facilitate container management.

### Step 3: Clone the Repository

Clone the project repository to your local machine:

```bash
git clone https://github.com/Lucas28reis/UOL_NEWS.git
cd UOL_NEWS
```

### Step 4: Open the Project in VS Code

Open the project directory in VS Code.

### Step 5: Build and Run the Docker Container

Press `Ctrl + Shift + P` in VS Code and select the option:

```plaintext
> Dev Containers: Rebuild Container Without Cache
```

This will build and run the configured Docker container for the project.

## How to Open the Project

To open the project, follow these steps:

1. **Open VS Code**:
   - Launch VS Code on your computer.

2. **Open the Project Folder**:
   - Go to `File` > `Open Folder...` and select the folder where you cloned the repository (e.g., `UOL_NEWS`).

3. **Open the Integrated Terminal**:
   - Open the integrated terminal in VS Code by going to `View` > `Terminal`.

4. **Build and Run the Container**:
   - In the integrated terminal, ensure you are in the project directory. Follow the Docker build and run instructions mentioned above.

5. **Run the Code**:
   - You can now navigate through the project files, edit the code, and run scripts directly in the integrated terminal.

Following these steps, you should be able to open and work on the news analysis project efficiently. If you need anything else, feel free to ask!
