for (var beer = 99; beer >= 1; beer--) {
  if (beer === 1) {
    var bottles = 'bottle';
  } else {
    bottles = "bottles";
  }
    var beerBottles = beer + " " + bottles + " of beer on the wall, " + beer + " " + bottles + " of beer! Take one down, pass it around, " + beer + " " + bottles + " of beer on the wall!";
    console.log(beerBottles);
}
