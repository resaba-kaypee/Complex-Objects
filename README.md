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

var gloveBoxContents = myStorage.car.inside["glove box"]; // Change this line
console.log(gloveBoxContents);
