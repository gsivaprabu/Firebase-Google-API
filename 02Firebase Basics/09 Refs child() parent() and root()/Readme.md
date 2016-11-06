# Refs child() parent() and root()

child() Method:-

	var url = "https://example.firebaseio.com";
	var moviesRef = new Firebase(url+"movies");
	var starsWarRef = moviesRef.child("star_wars");

parent() Method:-

	var url = "https://example.firebaseio.com";
	var starsWarRef = new Firebase(url+"movies/star_wars");
	var moviesRef = starWarsRef.parent();

parent() Method:-

	var url = "https://example.firebaseio.com";
	var starsWarRef = new Firebase(url+"movies/star_wars");
	var moviesRef = starWarsRef.root();