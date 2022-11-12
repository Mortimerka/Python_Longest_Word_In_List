# Python_Longest_Word_In_List
Longest word in list python open the "Open Me" or copy the code down here

words = ['a', 'aa', 'aaa', 'a']
max = len(words[0])
for index in range(0, len(words)):
    if max < len(words[index]):
        max = len(words[index])

for index2 in range(0, len(words)):
    if max == len(words[index2]):
        print(words[index2])
