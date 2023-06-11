# Java-Expt-9
# To add , remove, retrieve an element in an Array
# Aim:
To write a Java program to add , remove, retrieve an element in an Array.

# Algorithm
Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create an array with a name of your choice.

Step 3 : Using Scanner, Input a number or a element from the user.

Step 4 : Using for loop insert,remove,retrieve the input element at the end of the array.

Step 5 : Display the appended array in the terminal.

# Program

import java.util.*;<br>
class Main<br>
{<br>
    public static void main(String[] args) {<br>
        ArrayList<String> al = new ArrayList<String>();<br>
        System.out.println("Size of ArrayList: " + al.size());<br>
        al.add("Jawa");<br>
        al.add("KTM");<br>
        System.out.println("Elements of first ArrayList: " + al);<br>
        ArrayList<String> al2 = new ArrayList<String>();<br>
        al2.add("R15");<br>
        al2.add("RoyalEnfiled");<br>
        al2.addAll(al);<br>
        System.out.println("Elements of second ArrayList: " + al2);<br>
        al2.remove("R15");<br>
        System.out.println("Elements of ArrayList after deletion: " + al2);<br>
        System.out.println("Size of ArrayList: " + al2.size());<br>
        System.out.println("The element at 2nd index is: " + al2.get(2));<br>
    }<br>
}<br>

# Output:
![image](https://github.com/Anuayshh/Java-Expt-9/assets/127651217/a1541fee-8d40-4c37-bbad-c3e143983662)


# Result
We have successfully created a Java program to add , remove, retrieve an element in an Array.
