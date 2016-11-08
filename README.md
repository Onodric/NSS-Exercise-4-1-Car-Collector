# Car Manufactory

## Instructions

Follow the instructions in the comments below.

1. Create a new constructor function for the make of your favorite car.
1. It must inherit from the more general Car object.
1. Give it one property, named manufacturer, that holds a string value. For, example, this.manufacturer = "Ford".

1. Create a constructor function named after your favorite car model.
1. It must inherit from the specific make type you created in previous step.
1. Create some instance properties that are specific to the specific car model (e.g. horsepower, cargo capacity, etc.)

1. Being an avid car collector, you own three different cars all of same model from your favorite manufacturer.
  1. Create three new instances of your favorite car.
  1. Create a new property on each object to hold the license plate number for each car.

1. Now let's see some power of prototypal inheritance. Create a function for another model that's made by the manufacturer as your previous car. So if your first model was Fusion, make another one here for F150, for example.

1. Assign the prototype to the make you define above. Now both models will inherit the `manufacturer` property from the make function.

1. Now create an instance of this new car model to put in your garage. Remember to give it a plate number.
