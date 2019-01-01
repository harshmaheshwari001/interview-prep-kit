### JAVA8 Interview Questions

#### Questions on Streams

* What is Streams API?
* What is Parallel Streams and Streams in java8?
* When to Opt for Parallel Streams over normal Streams?
* Difference between Stream.of() vs IntStream.of() in java8?
	 
	 ``` int [] a = new int []{1,2,3,4,5};
	   IntStream.of(a).forEach(System.out::println)```

	 ```Stream.of(a).forEach(System.out::println);```

	 - Streams are designed to work with Object Type.
	 - IntStream are designed to work with primitive int datatype. 


* Method reference in JAVA8 - [Method Reference](https://dzone.com/articles/java-8-method-references)
