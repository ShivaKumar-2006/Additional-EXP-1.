# Additional-EXP-1.
##TITLE-SubSring
```
import java.util.Scanner;
public class InsertSubstring {
 public static void main(String[] args) {
   Scanner sc = new Scanner(System.in);
   System.out.print("Enter the main string: ");
   String mainString = sc.nextLine();
   System.out.print("Enter the substring to insert: ");
    String subString = sc.nextLine();
    System.out.print("Enter the position to insert the substring: ");
    int position = sc.nextInt();
    if (position < 0 || position > mainString.length()) {
    System.out.println("Invalid position!");
      } else {
     String firstPart = mainString.substring(0, position);
     String secondPart = mainString.substring(position);
     String resultString = firstPart + subString + secondPart;
     System.out.println("Resulting string: " + resultString);
     }
    sc.close();
    }
}
```
OUTPUT:
[output of add-exp1](substring.png)
