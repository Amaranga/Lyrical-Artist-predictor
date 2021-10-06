
# lyrical Artist predictor

## Description:
This project is about building a text classifacation model on song lyrics that predicts the artist from a piece of text.

It starts by asking the user to enter names of two artists and then it scrapes lyrics of the given artists from www.lyrics.com and merge and save them as CSV file. If the CSV files already exist in the folder the program will skip the scraping step. Then, after vectorizing the lyrics, a Naive Bayes model will be trained on lyrics by using the name of the artists as the target. Finally, the user can enter any new lyrics from either artist for the model to predict the name of the artist of that song.


#
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


## License

Free software: [MIT](https://choosealicense.com/licenses/mit/)
License
  