# oj.masaischool-contest-3367-problems



Say Hello 
Description

You are given a variable with the name,name, containing the name of the person

You have to print the name of the person as the output, along withHello

For example, the value stored inname = Prateek, then the required output will beHello Prateek


Input
The first and the only line of the input contains the value stored in the variablename


Output
Print the output as shown in the problem statement


Sample Input 1 

Prateek
Sample Output 1

Hello Prateek
Hint

In the sample test case, the value stored inname = Prateek

Therefore, the output isHello Prateek



####----------Coding Say Hello Prateek -------------#####
public static void sayHello(String name){
        //write your code here
        System.out.println("Hello " + name);
    }


-xx-xx--x--x-xx--x--x--x-x-x-x-x-x-x-x-x-x-x-x-x-x--x-x-x-x-x-x-x-xx-x-x-x--x-x-x-x-x-x-x-x-x-x-x-x--x-x-x-x-x-x-x-x--x-x-x-x--x-x--x--x-x-x---x--x-x-x




Find Product 
Description

You are given five numbers stored in variables with the following names

one, two, three, four, five

Find the product of the five values, and print it


Input
The first and the only line of the input contains five values, stored in the variablesone, two, three, four, five


Output
Print the product of the five values stored in the variablesone, two, three, four, five


Sample Input 1 

1 2 3 4 5
Sample Output 1

120
Hint

In the sample test case, the values stored in the variables areone = 1, two = 2, three = 3, four = 4, five= 5

The sum of the values is1 * 2 * 3 * 4 * 5 = 120, which is the required sum

####----------Coding Say print 120 -------------#####


public static void findProduct(int one,int two,int three,int four,int five){
        //write your code here
        int var = one * two * three * four * five;
        System.out.println(var);
    }



-xx-x-x-x--x-x-x--x-x-x-x-x-xx--x-x-x-x-x-x--x-x-x---x-x-x--x-x-x-x-x-x--x-x-x-xxxxxxx---------xxxxxxxxx-------------x----------------xxx-xxxxxxx


Operation on Numbers 
Description

You are given a number, stored in a variable with the namenumber. Perform the following operations on the value stored in the number

1. Multiply the value by 3
2. Add 7 after it
3. Subtract 10 from it
After performing all the above operations, print the updated value


Input
The first and the only line of the input contains the number, stored in the variablenumber

Constraints

1 <= N <= 30


Output
Print a single integer, denoting the updated value of the number stored, after performing all the operations, given in the problem statement


Sample Input 1 

4
Sample Output 1

9
Hint

In the sample test case, the value stored in the variablenumberis 4.

After multiplying the value by 3, the value gets updated to 12

After that, we add 7 to it, so the number gets updated to 19

Finally, we subtract 10 from it, so the value becomes 9, which is the final output



#####-------------coding on operations-------------------###########



  public static void operationOnNumbers(int number){
    //write your code here
    int var1 = number * 3;
    int var2 = var1 + 7;
    int var3 = var2 - 10;
    System.out.println(var3);
  }
