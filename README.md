# minecraft-chat-filter
A lil project to see if I can create a better chat filter for cathal

1. Use a .txt dictionary to run player input against a list of banned words.
2. If a banned word is part of a word in the dictionary, let the dict word show.
         Ex: banned word "straw" w/ "hay"
         If user enters "strawberry", "straw" will not be replaced with "hay", since straw is connected to berry
3. /cfilter add <word>|<word> all // adds a banned word to list | " " + #5
4. /cfilter remove <word> // removes banned word from list
5. /cfilter <word> all // for given word, removes all occurances of word regardless of what it's connected to
