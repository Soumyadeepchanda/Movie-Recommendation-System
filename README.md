# Movie Recommendation System

This is a movie recommendation system built using collaborative filtering. It recommends movies to users based on their historical ratings and similarities with other users.

## Overview

The movie recommendation system is designed to help users discover new movies based on their preferences and ratings. It analyzes user ratings and generates personalized movie recommendations using collaborative filtering techniques.

The system utilizes a user-item matrix to represent user ratings and calculates similarities between users or items. It then identifies similar users or items and recommends movies based on their ratings. The recommendation algorithm used in this system is collaborative filtering, which is a popular method for personalized recommendations.

## Technologies Used

- Python<br>
- Streamlit: Web framework for building interactive user interfaces<br>
- Pandas: Data manipulation library<br>
- Scikit-learn: Machine learning library for collaborative filtering<br>

## Installation

1. Clone the repository:<br>

git clone https://github.com/your-username/movie-recommendation-system.git<br>

2. Navigate to the project directory:<br>

cd movie-recommendation-system<br>

3. Install the required dependencies:<br>

## Usage

1. Prepare the dataset:<br>

   - Place the movie dataset in the `data` directory. The dataset should contain movie ratings provided by users.<br>

2. Run the application:<br>

streamlit run app.py<br>

3. Access the application:<br>

   Open your web browser and go to [http://localhost:8501](http://localhost:8501) to access the movie recommendation system.<br>

4. Interact with the application:<br>

   - On the home page, you can view movie recommendations for different users.<br>
   - Select a user from the dropdown menu to see personalized movie recommendations.<br>
   - You can also rate movies to improve the system's recommendations.<br>

## Screenshots

![WhatsApp Image 2023-07-19 at 15 36 40](https://github.com/Soumyadeepchanda/Movie-Recommendation-System/assets/93461379/ee257ddc-d258-4f7a-a0f6-cf6d8b30eed1)
*Screenshot of the home page with movie recommendations.*<br>
![WhatsApp Image 2023-07-19 at 15 38 22](https://github.com/Soumyadeepchanda/Movie-Recommendation-System/assets/93461379/a140c630-d243-4897-aa2f-a07b34762cff)
*Screenshot of personalized movie recommendations for a user.*<br>
![WhatsApp Image 2023-07-19 at 15 40 29](https://github.com/Soumyadeepchanda/Movie-Recommendation-System/assets/93461379/fd01ac13-f09a-44c9-852d-5475a404cc00)
*Screenshot of personalized movie recommendations for a user.*<br>


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
