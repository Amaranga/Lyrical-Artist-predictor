
# lyrical Artist predictor

## Description:
This project is about building a text classifacation model on song lyrics that predicts the artist from a piece of text.

It starts by asking the user to enter names of two artists and then it scrapes lyrics of the given artists from www.lyrics.com and merge and save them as CSV file. If the CSV files already exist in the folder the program will skip the scraping step. Then, after vectorizing the lyrics, a Naive Bayes model will be trained on lyrics by using the name of the artists as the target. Finally, the user can enter any new lyrics from either artist for the model to predict the name of the artist of that song.


## Badges


[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)

  
## Usage

- clone the repository

- run the Jupyter notebook

  
## Tech Stack
- Python
- requests
- BeautifulSoup
- Pandas
- scikit-learn

## Scripts
- lyrics_predictor_module: The main py file to run the program
- get_urls_and_scrape: Generates URLs of the first two pages of the artist's songs and scrape the lyrics using requests and BeautifulSoup
- clean_and_save: Clean the lyrics from special characters and removes duplicates and unwanted ones such as instrumental songs. Put them in a pandas DataFarme      with two columns, lyrics, and name of the artist and finally save the data as a CSV file.
- vectorize_and_train: Merges two CSV files that were created for each artist into one and vectorize the lyrics using TfidVectorizer. In addition, it trains Multinominal Naive Bayes model on the vectorized lyrics to predict the name of the artist for the given new lyrics

## License

Free software: [MIT](https://choosealicense.com/licenses/mit/)
License
  
