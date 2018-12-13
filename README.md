Author: Justin Lin


Data must be in the form:

var nodes = [
  {name: String, value: int},
  {name: String, value: int},
  ...
];

var links = [
  {source: nodes.name, target: nodes.name, weight: int, id: int},
  {source: nodes.name, target: nodes.name, weight: int, id: int},
  ...
];

*Check nodes.csv and links.csv for sample data


Objects variables:
nodes.name - refers to the name of each node, used for creating links
nodes.value - refers to the value of each node, used for constructing the bar chart
links.source, links.target - nodes for each link
links.weight - used for the stroke weight of each link
id - used for the color of the links

Sort by value - sorts bars by value descending
Sort by name - sorts bars in alphabetical order
Sort by links - sorts bars by number of links descending

Host: https://justinmlin.github.io/Linked-Bar-Chart/
