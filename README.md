# 4_sequence_repeat_iterators_and_generators_exercise
Create a class called sequence_repeat which should receive a sequence and a number upon initialization. Implement an iterator to return the given elements, so they form a string with a length - the given number. If the number is greater than the number of elements, then the sequence repeats as necessary. For more clarification, see the examples:

Test Code

result = sequence_repeat('abc', 5)
for item in result:
    print(item, end ='')

Output

abcab
