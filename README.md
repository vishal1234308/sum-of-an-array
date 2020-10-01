# sum-of-an-array


import jaav.util.*;
import java.util.Scanner;
class Main{
    public void main(String []args){
Scanner sc = new Scanner(System.in);
		int i,l;
		System.out.println("Enter a Number or String to be reversed: ");
		String n = sc.nextLine();
StringBuilder temp=new StringBuilder(n);

String reverse=temp.reverse().toString();

System.out.print(reverse);
		System.out.println();
		sc.close();
}
}









