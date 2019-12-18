# Greedy-Algorithms
Greedy algorithm utilizing repetitive resorting with new entries, then an optimized version that sorts in a priority queue constantly and is much faster.

These two files tackle optimal scheduling given a schedule then further entries with a time update so that you can't 
schedule events that already happened even if they would've been more optimal

Resort
- Implement an approach that re-sorts the remaining requests every time a new request is added or canceled, using Java’s 
built-in Quicksort. Then when a time is parsed by itself, all requests in the optimal schedule up 
to the time read can be executed (printed). Tested this approach successfully for 10,000 and 100,000 requests. 

Priority Queue
- Improved on the above time by realizing that we don’t need to re-sort the list over and over when we modify it, 
because we’re either removing single elements or inserting single elements with each step. A Priority Queue does exactly 
what we want, efficiently inserting elements without re-sorting, and still able to efficiently provide the best next element.
