# Spaceship Titanic Passenger Classification Project

Welcome to this comprehensive analysis of the Spaceship Titanic Passenger Dataset! The objective in this project is to predict whether a passenger was transported to another dimension, based on an extensive range of personal and transactional information. This project was completed with the collaboration of my classmates Fulin Zhang, Nicholas Sebald, Ruicong Wang, and Qinyi Miao. 

## Overview of the Dataset:

The [Spaceship Titanic Passenger Data](https://www.kaggle.com/competitions/spaceship-titanic/data) consists of detailed records for approximately 8,700 passengers.

### Dataset: `train.csv`

The `train.csv` file encompasses personal records of around 8,700 passengers, providing a rich dataset for our analysis and predictive modeling.

#### Feature Descriptions:

- `PassengerId`: A unique identifier for each passenger, formatted as `gggg_pp`. Here, `gggg` denotes the group number that the passenger is traveling with, and `pp` is their specific number within that group. Groups may consist of family members or other affiliations.
- `HomePlanet`: The home planet of the passenger, signifying the planet from which they departed, and typically representing their permanent residence.
- `CryoSleep`: A binary indicator reflecting whether the passenger opted for suspended animation during the voyage. Passengers in cryosleep remain in their cabins for the journey's duration.
- `Cabin`: The passenger’s cabin number, presented in the format `deck/num/side`. The `side` notation can be either 'P' for Port or 'S' for Starboard.
- `Destination`: The passenger’s destination planet upon disembarking from the Spaceship Titanic.
- `Age`: The age of the passenger.
- `VIP`: A binary indicator for whether the passenger availed special VIP services during the voyage.
- `RoomService`, `FoodCourt`, `ShoppingMall`, `Spa`, `VRDeck`: These features represent the amounts billed to the passenger for each of the Spaceship Titanic's luxurious amenities.
- `Name`: The full name of the passenger.
- `Transported`: This binary target variable indicates whether the passenger was transported to another dimension.
