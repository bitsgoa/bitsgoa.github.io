# bits.github.io

If you are familiar with HTML/CSS and git go ahead and submit a PR for your webpage.

Follow the usual way.
Fork the repo
Clone the repo
```
git clone https://github.com/bitsgoa/bitsgoa.github.io
```
make the following changes in your local branch.

Let's suppose your name is Raj Kumar.

If you want a basic html page then click on `Create new file` write whatever html you want and name it rajkumar.html, then add yourself in the list of your respective year (let's say 2015) in 2015.html and you are done.

If you want a fancy site something like `userX` where x belongs to [1, 2, ... 7] then create a folder named `rajkumar` and create a `index.html` file inside the folder as your main page and you can add more pages inside the folder and link them through `index.html`.

Once this is done.
Take the usual git way
```
git diff # make sure you didn't change anything else
git add rajkumar.html # or the folder rajkumar
git commit -m 'Added webpage for Raj Kumar'
git push -u origin master # assuming you are working on master
```

then create a PR and I'll merge it  :)
