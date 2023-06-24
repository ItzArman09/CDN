const app = require('express')();
app.get("/", (req, res) => {
  res.status(200);
res.json({works: "yes"});
});

app.listen(3000).then(() => console.log("k"));

module.exports = app;
