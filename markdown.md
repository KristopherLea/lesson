#Heading level 1

> Here is the first paragraph of my markdown file. This is my first time experimenting with markdown files. Markdown files seem to be an easier way to 
share information with others.


> This is my second paragraph example using markdown. I find that not only are markdown files to be easier to write, but they seem to also be more direct and concise in what the creator is attempting to convey. Being able to use the three tildes to write a block of Java is very interesting also.

1. Item 1
1. Item 2
1. Item 3

[Here is an external link to Youtube.](https://www.youtube.com)


import java.time.LocalDate;
import java.util.*;



class Main {
  public static void main(String[] args) {
Scanner scan = new Scanner(System.in);
System.out.println("Input name");
String x = scan.nextLine();
System.out.println(x);



System.out.println("email");
String y = scan.nextLine();
System.out.println(y);
scan.close();

LocalDate today = LocalDate.now();
System.out.println(today);
  }
}
