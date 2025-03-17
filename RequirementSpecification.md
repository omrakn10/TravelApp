1. Purpose

-This project is a mobile application designed to help travelers plan, track, and share their trips efficiently. 
-Users can create trips that can include travel details such as flights, accommodations, and activities. 
-Additionally, users can choose to share their trips publicly or keep them private.
-In this way, other users who are planning a trip can also get information on many subjects thanks to the trips added by the users.


2. User Roles

- Regular Users
	•	Can sign up, log in, and log out.
	•	Can create trips and add trip details.
	•	Can choose to share trips publicly or keep them private.
	•	Can edit or delete their own trips.
	•	Can browse and search public trips.

- Admin Role
	•	Can monitor public trips.
	•	Can remove inappropriate trips if needed.
	•	Has read-only access to all trips for moderation purposes.


3. Problems and Solutions

- Problems
	•	Users often struggle to organize trips efficiently.
	•	It is difficult to keep all travel-related details (flights, hotels, activities) in one place.
	•	Many apps do not provide a way to share complete trip details publicly.

- Solutions
	•	A structured trip planner where users can input trip details in a step-by-step manner.
	•	A centralized database using Firebase Firestore for easy trip management.
	•	A public trip-sharing feature, allowing users to make trips discoverable by others.

- Example Scenario:

  (Note: If the added trips are set to 'public', they will be visible to everyone. However, if they are not set to 'public', they will only be visible to the user on the 'my trips' screen.)

  Let's consider 2 users. Ali and Veli. 
  
  Ali lives in Balıksir and wants to go to Montenegro with his friends. They make their plans and set off. Before setting off, they create a new trip starting in Balıkesir and ending in Montenegro (the start, end and intermediate cities can be added either while creating the trip or by editing the trip during the trip) on our application. First, they go to Istanbul by bus. They add the city of Istanbul from the 'add city' section to the application and the bus from the 'add bus trip' section and write the price of the bus trip. Then they go to the airport. They add the price information about the way from bus terminal to airport. They land in Bosnia and Herzegovina by plane. They add the city of Bosnia from the 'add city' section. They rent a car from the Bosnia and Herzegovina airport. They add the car which they rented from airport to the application from the 'add rental car' section and write the amount they paid. If there is a tip or note that needs to be known when renting a car, they add it to the 'note' section in the rental car section of the trip, where limited words can be written. Then they go to Montenegro by car. They can add anything to the trip whenever they want, such as road fees, gas prices, etc. If they stayed in Bosnia and Herzegovina, they can add the hotel and price there from the 'add hotel' section. If they didn't, they can add the country where they stayed. In this way, Ali was able to create his own travel diary and help others.

  Veli is another user who wants to go to Montenegro. However, while planning his budget, he gets lost among the websites and then opens the application. He searches for Montenegro in the search section of the application and all the trips related to Montenegro appear. If he wants, he can filter his results (by price etc.). Then he comes across Ali's trip. Although Veli does not live in Balıkesir like Ali, the other information in the trip is very useful and he plans his trip thanks to the trips created by both Ali and other users. Veli creates his own trip and begins his adventure.

  Users will search for cities and will be able to access the specific information they are looking for with the filtering system. For example, a user searching for Spain will be able to search for trips that suit their budget. In addition, the dates of the trips will be kept. In this way, they will be able to learn where they went on which dates or where it was cheaper on which dates.

  Limited word notes can be added to things like trips, accommodations, flight tickets, etc. Thus, users will be able to share some tips with all other users. Nothing else can be written by hand except these notes. All of datas will be selected from the lists where the data in the database is shown. For example, when adding a city, it will be selected from the cities list.


4. Technologies
   
	•	Frontend: React Native (Expo)
	•	Database: Firebase Authentication & Firestore Database
	•	Data: API's

 
