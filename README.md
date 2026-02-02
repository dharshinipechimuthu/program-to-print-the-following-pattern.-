# program-to-print-the-following-pattern.-
(a) * 			(b)         * 			(c)  A 			 
      * * 		           		* * 			      A B 			 
      * * * 		        	* * * 			      A B C 			 
      * * * * 		    	 * * * * 			      A B C D 		 
      * * * * *             		* * * * *                                   A B C D E

(a)
n=int(input("Enter the limit:"))
for i in range(1,n+1):
    for j in range(1,i+1):
        print("*",end='')
    print(" ")

OUTPUT:

Enter the limit:5
* 
** 
*** 
**** 
***** 


(b)
n=int(input("Enter the limit:"))
for i in range(1,n+1):
    for k in range(n-i,0,-1):
        print(' ',end=' ')
    for j in range(1,i+1):
        print("*",end='')
    print(" ")

OUTPUT:

Enter the limit:5
        * 
      ** 
    *** 
  **** 
***** 

