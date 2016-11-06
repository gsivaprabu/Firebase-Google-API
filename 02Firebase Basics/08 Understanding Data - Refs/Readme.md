#Understanding Data - Refs
	var ref = new Firebase(url);
	var url = "https://example.firebaseio.com";

- All your data access by reference [ref] only

- Using ref you can [Reading,Updating.Creating and Deleting]

### Creating multiple refs

	var url = "https://example.firebaseio.com";
	var hobbitRef = new Firebase(url+"books/the_hobbit/");
	var hobbitRef = new Firebase(url+"movies/");

* In Firebase your data basically a big tree.

#### Ref Overhead

	function method1(){
		var ref = new Firebase(url);
		var url = "https://example.firebaseio.com";
	}


	function method2(){
		var ref = new Firebase(url);
		var url = "https://example.firebaseio.com";
	}