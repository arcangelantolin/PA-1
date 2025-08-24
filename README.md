# PA-1


The first function, alphabet_soup, takes an input string and rearranges its letters in alphabetical order. It works by converting the string into a list of characters, sorting the list, and then joining the characters back together into a new string. For example, calling alphabet_soup("hello") returns "ehllo", while alphabet_soup("hacker") returns "acehkr". This is also made to be case insensitive using the .lower() function

The second function, emotify, converts certain words in a sentence into emoticons. It uses a dictionary of key-value pairs where the keys are words like "smile", "grin", "sad", and "mad", and the values are their corresponding emoticons such as :), :D, :((, and >:(. The function splits the input string into individual words using the .split() function , checks if any of them match a dictionary key, and replaces them with the matching emoticon. For instance, the input "Make me smile" is transformed into "Make me :)", and "I am mad" becomes "I am >:(".

The third function, unpack, is used to separate the first, middle, and last elements of a list. It makes a duplicate of the input list to avoid modifying the original, then extracts the first and last elements using the .pop() function while grouping the remaining values as the middle portion. If the middle only contains a single value, it is returned as a single item rather than as a list. For example, calling unpack([1, 2, 3, 4, 5, 6]) will return 1 as the first element, [2, 3, 4, 5] as the middle, and 6 as the last.
