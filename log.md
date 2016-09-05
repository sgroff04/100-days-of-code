# 100 Days Of Code - Log

### Day 1: September 1, 2016

**Today's Progress**: I'm building a Markdown Previewer webapp. I created the React app using create-react-app, built out the file structure, and I was able to render markdown to HTML.

**Thoughts:** [create-react-app](https://github.com/facebookincubator/create-react-app) is awesome. Tomorrow I will look into using scss instead of css and start coding the React Components.

**Link to Github repo:** [Markdown Previewer](https://github.com/sgroff04/markdown-previewer)

**Today's Commit:** [Day 1](https://github.com/sgroff04/markdown-previewer/commit/3075994b6531f98777e65d6acac765e3b4cb5d33?diff=split)

### Day 2: September 2, 2016

**Today's Progress**: I finished building the React components and the app now works. Just needs styling.

**Thoughts:** My React skills were a little rusty. Tomorrow I will look into using scss to style the app.

**Link to Github repo:** [Markdown Previewer](https://github.com/sgroff04/markdown-previewer)

**Today's Commit:** [Day 2](https://github.com/sgroff04/markdown-previewer/commit/9b23c39b73660b3f3fb57d2fdb8e7d43a7eb6a04)

### Day 3: September 3, 2016

**Today's Progress**: I added Sass to the project, basic styling, project finished!

**Thoughts:** I learned how to eject react-create-app using ```npm run eject``` so I could add Sass to the project. Adding sass-loader to webpack was really easy.
```
loaders: [
  {
    test: /\.scss$/,
    loaders: ['style', 'css', 'sass']
  }
]
```

**Link to Github repo:** [Markdown Previewer](https://github.com/sgroff04/markdown-previewer)

**Today's Commit:** [Day 3](https://github.com/sgroff04/markdown-previewer/commit/e8e6ac77e3044b8c0bb1585c4ff063e154219d42)

### Day 4: September 4, 2016

**Today's Progress**: I built out the React project skeleton using react-create-app. I will also be using Bootstrap, Sass, Axios, and Fixed-date-table.

**Thoughts:** Today I spent the hour building out the project skeleton and installing the libraries I'll be using. Tomorrow I will build out the API using Axios to grab the Free Code Camp leaderboard data.

**Link to Github repo:** [Free Code Camp Campers Leaderboard](https://github.com/sgroff04/FCC-Leaderboard)

**Today's Commit:** [Day 4](https://github.com/sgroff04/FCC-Leaderboard/commit/b5f00675cc2a6d7f2d5414387825c0b5ddb468ed)

### Day 5: September 5, 2016

**Today's Progress**: I got the data from the API end-points using Axios. Did not get the data rendered on the page...

**Thoughts:** Axios was really simple to use. The `.get()` method returns a promise object. To access the data on the promise object you call the `.then()` method and pass it a callback function. `then` is a property on the promise object. You can simultaneously call multiple `.get()` methods by calling `.all()` which takes an array of promise getters.  

**Link to Github repo:** [Free Code Camp Campers Leaderboard](https://github.com/sgroff04/FCC-Leaderboard)

**Today's Commit:** [Day 5](https://github.com/sgroff04/FCC-Leaderboard/commit/be37494b5699e4c008115e8c60b293df69c0408a)