
### Dataset Description 

In this competition my task is to predict wheter a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with the spacetime anomaly. To help make these predictions I am provided with a set of personal records recovered from the ship's damaged computer system. 


There is a train.csv that is personal records for ~8700 passengers to be used for training data. 

- **PassengerID** - Unique ID for each passenger. Each ID is in the form of gggg_pp, where gggg is the group the passenger is in, with pp being their number within the group 
- **HomePlanet** - The planet the passenger departed from, typically their planet of permanent residence. 
- **CryoSleep** - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins. 
- **Cabin** - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard. 
- **Destination** - The planet the passenger will be debarking to. 
- **Age** - The age of the passenger. 
- **VIP** - Whether the passenger has paid for special VIP service during the voyage. 
- **RoomService, FoodCourt, ShoppingMall, Spa, VRDeck** - amount passenger has spent at each amenity.
- **Name** - name of the passenger. 
- **Transported** - Whether the passenger was transported to another dimension. This is the target. 

