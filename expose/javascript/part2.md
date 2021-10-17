1. 3 would be printed on the console because at the end of the three loops, i would be incremented three times from i=0, thus i would be 3 

2. 150 would be printed on the console because at the end of the three loops, discountedPrice = prices[2]*(1-discount) = 300*(1-0.5) = 150

3. 150 would be printed on the console because at the end of the three loops, discountedPrice = prices[2]*(1-discount) = 300*(1-0.5) = 150, and finalPrice = Math.round(discountedPrice * 100) / 100 = Math.round(150*100) / 100 = 150

4. the function would return the array discounted, which is [50,100,150]. each time the discounted price is being calculated, it's been pushed to discounted.

5. It would cause an error because variable i is declared by let, so we cannot access it outside it's block.

6. It would cause an error because variable discountedPrice is declared by let, so we cannot access it outside it's block.

7. 150 would be printed on the concole because at the end of the three loops, discountedPrice = prices[2]*(1-discount) = 300*(1-0.5) = 150, and finalPrice = Math.round(discountedPrice * 100) / 100 = Math.round(150*100) / 100 = 150. Here finalPrice is in the same block we declared it, so we can access it.

8. the function would return the array discounted, which is [50,100,150]. each time the discounted price is being calculated, it's been pushed to discounted. Here discounted is in the same block we declared it, so we can access it.

9. It would cause an error because variable i is declared by let, so we cannot access it outside it's block.

10. 3 would be printed on the console, because length = prices.length = 3, and it's declared in the same block.

11. the function would return the array discounted, which is [50,100,150]. each time the discounted price is being calculated, it's been pushed to discounted. Here altough discounted is const, we can push values to it.

12. 
A. student.name;

B. student["Grad Year"];

C. student.greeting();

D. student["Favorite Teacher"].name;

E. student.courseLoad[1];

13. 
A. ‘32’ since integers map to their exact string representation

B. 1 since '3' is mapped to integer 3

C. 3 since null is mapped to 0

D. '3null" since null is mapped to string 'null'

E. 4 since true is mappe to 1

F. 0 since false and null are both mapped to 0

G. '3undefined' since undefined is mapped to string 'undefined'

H. NaN since '3' is mapped integer3 and undefined is mapped to NaN, 3 - Nan = Nan

14. 
A. true since '2' is mapped to integer 2

B. false since they're compared as strings, not numbers. and '12'<'2' as strings

C. true since '2'is converted to number 2

D. false === checks strictly equal, it returns flase for values that are not the same type

E. false since true is mapped to number 1

F. true since Boolean(2) converts 2 to the boolean value true

15. == checks if two variables are equal after being converted to the same type, other the other hand === checks if two variables are strictly equal, 

16. part2-question16.js

17. [2,4,6] First as we entered the function modifyArray, a empty const array newArr is created, then we run the loop three times(since the length of the input array is 3), each time we run the loop we call the function doSomething(it mutiply its input by 2) with the correspond elemnt in the input array, then push the result to newArr. So eventually newArr is filled with each elments in the input array*2. Thus newArr would be [1*2,2*2,3*2] = [2,4,6] ,and this is being returned.

18. part2-question18.js

19. 
1
4
3
2
It should print 1, then wait a second then print 2, then print 3, then print 4