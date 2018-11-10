# Complex-Objects
this objects that properties with a value of array
var myMusic = [
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [ 
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  },
  {
    "artist": "Michael Jackson",
    "title": "Beat It!",
    "release_year": 1985,
    "formats": [
      "CD",
      "MP3",
      "8T",
    ]
  }// Add record here
];

// how to access property values
// Setup
var myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};


// Accessing Nested Arrays

var myPlants = [
  { 
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }  
];



var secondTree = myPlants[1].list[1];
console.log(secondTree)

var gloveBoxContents = myStorage.car.inside["glove box"]; // Change this line
console.log(gloveBoxContents);
