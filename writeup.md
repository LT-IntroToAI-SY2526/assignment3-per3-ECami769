# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
I learned about match and pattern, mat and pat. I also began to understand the way the coding worked for the actions becuase it was very repetative, I was able to create my own pretty quickly which was nice.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
The chatbox system asks the user what they need, the user responses. Then the chatbot searches through the response and the database to find any matches, if it does it follows the pattern to see what to return to the user. 


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use? It can be useful for research purposes such as a school project or something that you want to learn about. It's quick and provides a direct response. To extend this we can continue to add more information to the movie database. Additionally, if we really wanted to we could expand it to being not just a movie database, but also include shows or something like that. As for improvement for practical use, I'm not really sure how we could shorten some programming that we have written to make the process more practical.