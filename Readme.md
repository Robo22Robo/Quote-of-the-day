# Quote of the Day WebApp

Create a webapp to display a random quote using HTML, CSS and Javascript

## Rules

- Setup a consistent project structure
- Use vanilla javascript (no JQuery but Bootstrap css is ok)
- Only use [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/) as resource
- You will work on your own: it's an individual assignment  


***Bonus point if you user Git properly!***  
Commit & push your working code. Then create a new branch, implement a new feature and merge it when you finished. Use the commit message to document your work. Then start again with the next feature (if any).  
[Review the process here, if you need](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)


## Technical requirements

Create a function that returns a random quote from the array of quotes that's given (check below "Sample Data"). Remember that there's a nice function for random numbers in the [MDN documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math) for *Math.rand()*.

Sometimes it's a good idea to create multiple functions, that do one specific thing only, to make the code more readable and easier to maintain / extend.

If you think they can be useful put some comments to document your code, but remember don't tell-stories (review [Don't be a Ninja](https://codepen.io/leandro_berlin/pen/GzKWwv?editors=0010)). Add the needed JavaScript to load a new random quote, when the button below the quote is used.

## Demo

You're very welcome to customize the UI of your webapp. Here a demo with the minimum requirments.

<img alt="mockup" src="demo.gif">


## Sample Data:
Here a list of random quotes you can use for your app  
```javascript
  const quotes = [
    "Our greatest weakness lies in giving up. The most certain way to succeed is always to try just one more time.",
    "Don't watch the clock; do what it does. Keep going.",
    "The secret of getting ahead is getting started.",
    "Well done is better than well said.",
    "You miss 100% of the shots you don’t take.",
    "A goal is a dream with a deadline.",
    "Outstanding people have one thing in common: An absolute sense of mission.",
    "Trying is winning in the moment.",
    "Fall down seven times and stand up eight.",
    "You just can't beat the person who never gives up.",
    "There is little success where there is little laughter.",
    "We cannot solve our problems with the same thinking we used when we created them."
  ];
  ```
