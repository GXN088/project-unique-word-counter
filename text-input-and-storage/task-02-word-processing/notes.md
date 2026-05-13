Word Processing


Now we'll process each word by removing punctuation and converting to lowercase. This will help us count words accurately regardless of their case or surrounding punctuation.

String word = "Hello!";
// Remove punctuation and convert to lowercase
word = word.replaceAll("[^a-zA-Z ]", "").toLowerCase();
System.out.println(word);
// prints: hello
