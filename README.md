# nosql-challenge
module 12
1. In this assignment we given the he UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. 
2. We Imported the establishments.json file to mongodb using mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
3. We added new restuarent Penang Flovours to collection
4. we updated BusinessTypeID of new restuarent Penang Flovours, deleted the documents contain the Dover Local Authority and changed data types of latitude, longitude and RatingValue
5. Then we ran some quries to find out 
    a. Which establishments have a hygiene score equal to 20? 
    b. Which establishments in London have a RatingValue greater than or equal to 4?
    c. What are the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
    d. How many establishments in each Local Authority area have a hygiene score of 0?