# Football Player Wage Prediction Project

## Project Overview
This project aims to predict the wages of football players based on various player attributes such as overall rating, potential, physical attributes, and technical skills. The dataset includes detailed information on thousands of football players, providing the necessary features to build predictive models that can accurately estimate a player's weekly wage in euros.

## Objectives
1. **Predict football player wages** using a variety of machine learning models.
2. **Analyze and understand the key attributes** that influence player wages.
3. **Develop a reliable predictive model** that can assist football clubs in making data-driven financial decisions.
4. **Compare the performance of different regression models**, specifically Random Forest and Support Vector Regression (SVR).

## Dataset
The dataset consists of 49 input variables, including 9 categorical variables and 40 numerical variables. These variables are grouped into categories to facilitate easier analysis and better understanding of player characteristics. 

1. **Player Identification and Personal Information**:
   - **name**: Name of the player.
   - **full_name**: Full name of the player.
   - **birth_date**: Date of birth of the player.
   - **age**: Age of the player.
   - **height_cm**: Player's height in centimeters.
   - **weight_kgs**: Player's weight in kilograms.
   - **nationality**: Player's nationality.
   - **body_type**: Player's body type.

2. **Player Position and Role**:
   - **positions**: Positions the player can play.
   - **national_team_position**: Position in the national team.
   - **national_team**: National team of the player.
   - **national_jersey_number**: Jersey number in the national team.

3. **Player Performance and Reputation Ratings**:
   - **overall_rating**: Overall rating of the player in FIFA.
   - **potential**: Potential rating of the player in FIFA.
   - **international_reputation (1-5)**: International reputation rating from 1 to 5.
   - **national_rating**: Rating in the national team.

4. **Financial Information**:
   - **value_euro**: Market value of the player in euros.
   - **wage_euro**: Weekly wage of the player in euros.
   - **release_clause_euro**: Release clause of the player in euros.

5. **Technical Attributes (Skill-Based)**:
   - **crossing**: Ability to deliver accurate crosses into the box.
   - **finishing**: Ability to score goals in 1-on-1 situations or from shots.
   - **heading_accuracy**: Accuracy of heading the ball.
   - **short_passing**: Accuracy in short passing.
   - **volleys**: Ability to score from volleyed shots.
   - **dribbling**: Ability to maneuver with the ball past opponents.
   - **curve**: Ability to bend the ball, particularly for shots and crosses.
   - **freekick_accuracy**: Accuracy of free kicks.
   - **long_passing**: Ability to make accurate long-range passes.
   - **ball_control**: Ability to control the ball upon receiving it.

6. **Physical Attributes (Athleticism)**:
   - **acceleration**: Speed in getting to maximum pace.
   - **sprint_speed**: Maximum speed while running.
   - **agility**: Ability to change direction quickly.
   - **reactions**: Speed of response to events on the field.
   - **balance**: Ability to maintain stability while running, shooting, or passing.
   - **jumping**: Ability to jump for headers or aerial challenges.
   - **stamina**: Endurance to perform throughout the match.
   - **strength**: Physical power to hold off opponents and maintain possession.

7. **Attacking Attributes**:
   - **shot_power**: Power behind a player’s shot.
   - **long_shots**: Ability to shoot effectively from long distance.
   - **positioning**: Ability to be in the right place during offensive plays.
   - **vision**: Ability to spot opportunities for through balls or long passes.
   - **penalties**: Accuracy in taking penalties.

8. **Defensive Attributes**:
   - **standing_tackle**: Ability to dispossess opponents through standing tackles.
   - **sliding_tackle**: Effectiveness in sliding tackles to win the ball.
   - **interceptions**: Ability to read the game and intercept passes.
   - **marking**: Ability to stay close to and limit the effectiveness of opposing players.

9. **Mental Attributes**:
   - **composure**: Ability to remain calm under pressure.
   - **aggression**: Willingness to press and tackle opponents, displaying intensity in play.

10. **Special Skills**:
   - **preferred_foot**: Player's dominant foot (right or left).
   - **weak_foot (1-5)**: Ability to use the weaker foot for passing and shooting.
   - **skill_moves (1-5)**: Proficiency in performing skill moves like tricks and dribbles.

## Project Workflow
1. **Exploratory Data Analysis (EDA)**:
   - Analyze distributions of key variables.
   - Handle missing data, outliers, and apply necessary transformations to skewed distributions.
   - Investigate correlations between features and wages.
   
2. **Feature Engineering**:
   - Create relevant features based on the dataset to enhance model performance.
   - Scale and normalize data to prepare it for model training.

3. **Modeling**:
   - Build two machine learning models: Random Forest Regressor and Support Vector Regressor (SVR).
   - Hyperparameter tuning via **GridSearchCV** to optimize model performance.
   - Evaluate models using **Root Mean Squared Error (RMSE)** and **R-squared**.

4. **Model Evaluation**:
   - Compare the results of both models based on accuracy and performance metrics.
   - Select the best-performing model for wage prediction.

## Contact
For any questions or contributions, please reach out via email: votuanhvn@outlook.com).
