
# Anime Recommendation System

## Project Description

This project is an Anime Recommendation System that leverages clustering and content-based filtering techniques to recommend anime based on genre similarities and other attributes. It uses a combination of machine learning algorithms and data visualization tools to provide meaningful recommendations to users.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/anime-recommendation-system.git
    cd anime-recommendation-system
    ```

2. Create and activate a virtual environment:
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Data Preprocessing and Clustering:**
    - The notebook performs data preprocessing, including handling missing values and encoding categorical data.
    - It uses clustering algorithms to group similar anime based on their genres and other attributes.

2. **Recommendation Functionality:**
    - You can input the name of an anime, and the system will recommend similar anime based on precomputed clusters and genre similarities.
    - The recommendations are displayed in a user-friendly format with details like anime name, English title, genre, and similarity percentage.

3. **Running the Recommender System:**
    - To run the recommender system, execute the notebook or script that initializes a Tkinter GUI for user input.
    - Example usage:
        ```sh
        python app.py
        ```
4. **Tools and Technologies:**
    Python, Pandas, Scikit-learn, TensorFlow, Keras, and tkinter
   
## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/your-feature
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/your-feature
    ```
5. Open a pull request.

## Acknowledgements

- The dataset used in this project is sourced from [MyAnimeList](https://myanimelist.net/).
- Special thanks to the contributors of various Python libraries such as Pandas, Scikit-learn, and Seaborn.
