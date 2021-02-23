## Data:

- **Features**

  - *DateCrawled* — date profile was downloaded from the database
  - *VehicleType* — vehicle body type
  - *RegistrationYear* — vehicle registration year
  - *Gearbox* — gearbox type
  - *Power* — power (hp)
  - *Model* — vehicle model
  - Mileage — mileage (measured in km due to dataset's regional specifics)
  - *RegistrationMonth* — vehicle registration month
  - *FuelType* — fuel type
  - *Brand* — vehicle brand
  - *NotRepaired* — vehicle repaired or not
  - *DateCreated* — date of profile creation
  - *NumberOfPictures* — number of vehicle pictures
  - *PostalCode* — postal code of profile owner (user)
  - *LastSeen* — date of the last activity of the user

  **Target**

  *Price* — price (Euro)

## Goal:

Comparing gradient boosting methods with random forest, decision tree, and linear regression and analyzing the speed and quality of the models.

## Libraries used:

pandas

catboost

time

sklearn.ensemble

sklearn.linear_model

sklearn.metrics

sklearn.model_selection

sklearn.preprocessing

lightgbm