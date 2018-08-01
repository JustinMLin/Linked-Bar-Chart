Author: Justin Lin


Data must be in the form:

var nodes = [
  {name: String, value: int},
  {name: String, value: int},
  ...
];

var links = [
  {source: nodes.name, target: nodes.name, weight: int, id: 1},
  {source: nodes.name, target: nodes.name, weight: int, id: 1},
  ...
];


Objects variables:
nodes.name - refers to the name of each node, used for creating links
nodes.value - refers to the value of each node, used for constructing the bar chart
links.source, links.target - nodes for each link
links.weight - used for the stroke weight of each link
id - used for the color of the links
