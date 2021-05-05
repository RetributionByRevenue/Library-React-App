Hosted On Heroku:  https://shielded-reef-28743.herokuapp.com <br>
👀👀👀I had to wrap my API url around a proxy in order to conform to the strict CORS regulations on Heroku. Although unlikely, when searching for a book, the proxy can be slow or sometimes stop working altogether so please refresh the Heroku app and try again!👀👀👀  
<br>

***1.	How long did you spend on the coding assignment? 
a.	What would you add to your solution if you had more time?***
<br>
If i had more time, i would add a redux component to my library search website to add better state & memory tooling.  To be specific, redux would be great for remembering user typed book name and ISBN searches made on the search bar (react component) embedded in my website.  Naturally, i would add a section to my website that would show previous search results fetching from the redux array and displaying them. In total, i spent about 3 hours on react and api coding, and 3 hours on css styling and including accessibility paradigms.

***2.What was the most useful feature that was added to the latest version of your chosen language? Please include a snippet of code that shows how you've used it.***
<br>
The most powerful and latest feature i have used in my library react application was the JavaScript arrow function.   Essentially, the arrow function is a very useful and powerful addition to the JavaScript programming language, as it is used very often in react for communication between props and components.  The arrow function eliminates the "this" keyword and uses the previous context of "this", so it can be used to make fast and efficient compared to its counterpart in the traditional way of programming functions.  
```
handleChange = (e) => {
this.setState({searchQuery:  e.target.value})
}

handleClick = () => {
this.callAPI(this.state.searchQuery, 0)
} 
//example of 
```
***3.How would you track down a performance issue in production? Have you ever had to do this?*** 
<br>I would track performance by using lighthouse to check all relevant metrics including Performance, Accessibility, Best Practices, and Search engine optimization.  In my previous job and back before google released lighthouse, i would use the Lattice Performance Management tool-chain to check for the relevant performance metrics mentioned above. 

***4.How would you improve the API that you just used?***
<br>I would standardize the order orientation of json elements that would be returned from my API call.   For example, the API sometimes returns a book description and other the other time it dose not.  When i was programming this assessment, i thought i made errors in my JavaScript code because i would pass a null value.  However, upon closer inspection, i noticed that if something does not exist for a particular book, it would not be passed into the json i fetch.  The solution would to simply include something like { description: "none" } so it could help developers in the programming process.  This is why i have to include many if statements to catch possible json criteria omissions so my code would not break.  

***5. Please describe yourself using correctly formatted JSON.***
```
{
personality: "easy going",
hobbies: ["playing guitar", "travelling", "making new friends", "JavaScript programming"],
favourite video games: ["League of Legends", "Paper Mario"],
YouTube Channel: "www.youtube.com/PythonForTrading"
}
```
