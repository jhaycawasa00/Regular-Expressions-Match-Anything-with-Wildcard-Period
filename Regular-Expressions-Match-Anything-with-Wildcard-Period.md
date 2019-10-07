
# Description

Regular Expressions: Match Anything with Wildcard Period
Sometimes you won't (or don't need to) know the exact characters in your patterns. Thinking of all words that match, say, a misspelling would take a long time. Luckily, you can save time using the wildcard character: .

The wildcard character .will match any one character. The wildcard is also called dotand period. You can use the wildcard character just like any other character in the regex. For example, if you wanted to match "hug", "huh", "hut", and "hum", you can use the regex /hu./to match all four words.

let humStr = "I'll hum a song";
let hugStr = "Bear hug";
let huRegex = /hu./;
humStr.match(huRegex); // Returns ["hum"]
hugStr.match(huRegex); // Returns ["hug"]


# Instruction

Complete the regex unRegexso that it matches the strings "run", "sun", "fun", "pun", "nun", and "bun". Your regex should use the wildcard character.


# Test

You should use the .test()method.
You should use the wildcard character in your regex unRegex
Your regex unRegexshould match "run"in "Let us go on a run."
Your regex unRegexshould match "sun"in "The sun is out today."
Your regex unRegexshould match "fun"in "Coding is a lot of fun."
Your regex unRegexshould match "pun"in "Seven days without a pun makes one weak."
Your regex unRegexshould match "nun"in "One takes a vow to be a nun."
Your regex unRegexshould match "bun"in "She got fired from the hot dog stand for putting her hair in a bun."
Your regex unRegexshould not match "There is a bug in my code."
Your regex unRegexshould not match "Catch me if you can."



# Challenge seed

let exampleStr = "Let's have fun with regular expressions!";

let unRegex = /change/; // Change this line

let result = unRegex.test(exampleStr);



# Solution

let exampleStr = "Let's have fun with regular expressions!";

let unRegex = /.un/; // Change this line

let result = unRegex.test(exampleStr);
