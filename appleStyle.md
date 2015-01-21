# Appleの公式っぽいスタイル

Swift公式ドキュメント
([https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language]())より

## Collection Types

### Iterating Over a Dictionary

You can iterate over the key-value pairs in a dictionary 
with a for-in loop. Each item in the dictionary is returned 
as a (key, value) tuple, and you can decompose the tuple’s members 
into temporary constants or variables as part of the iteration:

	for (airportCode, airportName) in airports {
    	println("\(airportCode): \(airportName)")
	}
	// YYZ: Toronto Pearson
	// LHR: London Heathrow
	
For more about the for-in loop, see [For Loops]().