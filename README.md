# EXERCISE 1
a) 1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz Fizz 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 FizzBuzz  

b)Start
STEP 1.
Initialize n=1

STEP 2.
a) if (number is divisible by 3 and 5)
	then print "FizzBuzz", Go to STEP3
b) if (number is divisible by 3)
	then print "Fizz", Go to STEP3
c) if (number is divisible by 5)
	then print "Buzz", Go to STEP3
d )print n

STEP 3. 
Increment n by 1 (n++) 
if n<=30 Go to Step 2
else stop

c)program
	int main()
	{
	    int i;
	    for (i=1; i<=100; i++)
	    {

		if ((i%3 == 0) && (i%5 == 0))       
		    printf ("FizzBuzz\t");   


		else if ((i%3) == 0)   
		    printf("Fizz\t");                


		else if ((i%5) == 0)                      
		    printf("Buzz\t");                

		else           
		    printf("%d\t", i);                

	    }

	    return 0;
	}
