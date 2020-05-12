1 == 1.0 // true
1.eql? 1.0 // false

eql? method would return true if both sides had the same hash key. it is used by HASH to test members for equality. whereas == is a Numeric function can be performed across conversion.