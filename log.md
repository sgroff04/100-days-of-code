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

### Day 6: September 6, 2016

**Today's Progress**: I finally got the data rendered to the page and started building the table.

**Thoughts:** The `render()` method was trying to render object properties on an undefined array (ex. `this.state.recent[0].username`) since the Promise has not yet returned any data to `this.state`. This was causing an error and the app to crash.

**Link to Github repo:** [Free Code Camp Campers Leaderboard](https://github.com/sgroff04/FCC-Leaderboard)

**Today's Commit:** [Day 6](https://github.com/sgroff04/FCC-Leaderboard/commit/d55f8639347203b0ee2b323bd1855876cad88fd6)

### Day 7: September 7, 2016

**Today's Progress**: I broke each Table cell into seperate `<Cell />` components and rendered the proper data for each column cell in the table.

**Thoughts:** Still learning and getting used to using Fixed-data-table. I was able to render the proper data for each table column and broke each column cell into their own stateless components Tomorrow I need to add some basic styling to make the data resemble a table.

**Link to Github repo:** [Free Code Camp Campers Leaderboard](https://github.com/sgroff04/FCC-Leaderboard)

**Today's Commit:** [Day 7](https://github.com/sgroff04/FCC-Leaderboard/commit/a33202c08e13b74cbdf5bc6616717d855b7d5406)

### Day 8: September 8, 2016

**Today's Progress**: I finished the styling for the Leaderboard, nothing exciting.

**Thoughts:** It now looks like a Table, yay.

**Link to Github repo:** [Free Code Camp Campers Leaderboard](https://github.com/sgroff04/FCC-Leaderboard)

**Today's Commit:** [Day 8](https://github.com/sgroff04/FCC-Leaderboard/commit/46d3601a17e738d7a70f3e0578886fee5010b270)

### Day 9: September 9, 2016

**Today's Progress**: The table data can now be sorted by Top 100 Campers over the past 30 days or all time. Project finished!

**Thoughts:**  This project shows how fast React is at rendering data. I'm going to use Redux for the rest of my React projects going forward.

**Link to Github repo:** [Free Code Camp Campers Leaderboard](https://github.com/sgroff04/FCC-Leaderboard)

**Today's Commit:** [Day 9](https://github.com/sgroff04/FCC-Leaderboard/commit/2294bff766cf9523519e45bdae0e35e171d258cb)

### Day 10: September 12, 2016

**Today's Progress**: Got the project setup and planned

**Thoughts:**  react-create-app is great

**Link to Github repo:** [Free Code Camp Recipe Box](https://github.com/sgroff04/Recipe-Box)

**Today's Commit:** [Day 10](https://github.com/sgroff04/FCC-Leaderboard/commit/2294bff766cf9523519e45bdae0e35e171d258cb)