# Inspiration
Spontaneous trips with friends is always a fun thing to plan. However, it is not so feasible when your friends are in different parts of the country. Fortunately, with Travel Planet, this process can be made more simple.  We want friends to be there for each other and what better way can that be done by meeting up with your friend and exploring a new place?

# What it Does 
Travel Planet can give a destination where you and your friend can meet and automatically finds the cheapest airline price. The program only requires that the address of both you and your friend so that the magic can take place. The best part about this program is that the destination given will be completely random, thus feeding into the spontaneous trip vibe.
 
 # How We Built It
We created Travel Planet using Java for the backend portion of the program. We used an API called TravelPayouts and used HTTP GET to retrieve information from the API. We utilized JSON to parse all of the data so that only relevent information is needed to present to the user. Java Server Pages was also used in order to make sure our Java program. 

# Challenges We Ran Into
One problem during the beginning was finding the right API to use. The number of times we could request data from the API limited our testing abilities. Moreover, we had some difficulties implementing the API in our using JavaScript. We overcame this solution by writing in Java and then creating a GUI to present the information in a clean way. Another challenge was creating the algorithm using the required parameters for the API. Since the destination was random, we could not directly use the API since the destination was needed ahead of time. Therefore, we created the algorithm to use an array containing many destinations and then random destinations are chosen, where the cheapest route is then displayed.

# Accomplishments That We're Proud Of
We are proud that we were able to implement API in our program. There were many challenges that were thrown at us when using an API and we were able ultimately able to use it as needed. We are proud of being able to use JSON properly as well. If we were not able to figure out JSON, there would have been excess information that would have cluttered the screen.

# What We Learned
Implementing an API in a program is something that we are proud to say that we learned. We are glad that we figured out how to reference an API using a url. Even if we did not use JavaScript in our final program, we still learned how to use JavaScript in web design and how we can use it in web design. 

# What's Next for Travel Planet
Our next step is to be able to add more friends to our program so that a group of people can meet up at one single place. We also would like to find more resources so that we can use APIs without restrictions and provide more for our users. 
