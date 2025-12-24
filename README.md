# Song and Artist Identification Model

This project provides a simple text-identification model that predicts the Song Title and Artist from a snippet of lyrics using the Spotify Million Song Dataset.

## Features
- Loads and preprocesses the dataset (tokenization, stop-word removal)
- Uses TF-IDF vectorization and Nearest Neighbors for text similarity
- Identifies the most likely song and artist for a given lyrics snippet

## Technologies Used
- Python
- pandas
- scikit-learn
- re

## Usage
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open `search_song.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells to load the model.
4. Enter a lyrics snippet when prompted to identify the song and artist.

## Example
```
Enter a lyrics snippet to identify the song and artist: Making somebody happy is a question of give and take
Predicted Song: Make Somebody Happy
Predicted Artist: Santana
Similarity Distance: 0.4096
```

## Dataset
- The model uses `Spotify Million Song Dataset_exported.csv` (not included due to size).

## Notes
- The model is based on text similarity and may not be perfect for very short or ambiguous snippets.
- For best results, use a distinctive line from the song lyrics.
