#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(1). Even though this is a loop we will only go thru it twice which is constant O(2) we drop the constant with big O meaning O(1) time. We can set N to any number and n*n*n will be equal to 2 run thrus or (a+n*n) + (a+n*n) == n*n*n

b) O(n log n) the first loop iterates thru all of n making it O(n). The second loop is shorter as j grows at a faster rate then n. O(n) \* O(log n) == O(n log n)

c) O(n) one recursive call not inside of any loop will always be O(n)

## Exercise II

my proposed solution would be to start from the middle floor and to drop the egg. If it breaks then we go half way down and try it again. If it did not break then we go half way up from there and try it again. We continue this process until we find the floor with 1 floor difference where it breaks and does not break. IE: floor 12 egg breaks, floor 11 egg does not break. this is a O(log n) solution because the number of floors is cut in half each test we make.
