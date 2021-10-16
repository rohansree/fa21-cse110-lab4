1. The bug was that num1 and num2 were being interpreted and added together as strings, so they were concatenated into result instead of added together as numbers. 
2. I casted the strings num1 and num2 to integers using parseInt(). I then added the two casted integers together to get a result that was mathematically accurate.
