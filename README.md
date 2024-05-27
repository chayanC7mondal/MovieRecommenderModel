# 🎬 Basic Movie Recommendation Model 📽️

Welcome to the Movie Recommendation Model repository! This project builds a machine learning model to suggest movies based on user preferences using collaborative and content-based filtering. 🍿✨

## Features 🌟
- **Hybrid Model:** Combines collaborative and content-based filtering.
- **Jupyter:** Do open the file on jupyter for ease of use.

## Installation 💻
Clone this repository and install dependencies:
```bash
git clone https://github.com/chayanC7mondal/MovieRecommenderModel.git
cd movie-recommendation-model
pip install -r requirements.txt
```

## Usage 🚀
1. **Prepare Data:**
   ```bash
   python data_preparation.py --input dataset/movies.csv --output processed_data/
   ```
2. **Train Model:**
   ```bash
   python train_model.py --data processed_data/
   ```
3. **Make Recommendations:**
   ```bash
   python recommend.py --user_id 123
   ```

## Dataset 📊
Using the MovieLens dataset. Download it [here](https://grouplens.org/datasets/movielens/latest/).

## Contributing 🤝
1. Fork the repository.
2. Create a branch (`git checkout -b feature-branch`).
3. Commit changes (`git commit -m 'Add feature'`).
4. Push (`git push origin feature-branch`).
5. Create a pull request.



Enjoy your movie recommendations! 🎉🍿

