# Road-Safety

The first program (First Detection) detects the number plates of cars passing and stores the number plate and the timestamp into a database.

The second program (Second Detection) detects the number plates of cars passing and retrieves the entry of the timestamp that has been stored in the database by the first detection, if it exists. Using the difference between the timestamp and the distance between the two logging station, it calculates the average speed. If this average speed is greater than the maximum speed in the area, then the number plate of the car and the average speed will then be appended to the car.csv. The car.csv file contain the list of all the car which have average speed greater than the maximum speed.

### Tools and Languages Used:
* Python
* MySQL

### Packages:
* CV2
* matplotlib
* numpy
* imutils
* easyocr
* datetime
* mysql.connector
