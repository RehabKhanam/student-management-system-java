import java.util.Scanner;

public class StudentManagementSystem {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter Student Name: ");
        String name = sc.nextLine();

        System.out.print("Enter Student Marks: ");
        int marks = sc.nextInt();

        System.out.println("\nStudent Details");
        System.out.println("Name: " + name);
        System.out.println("Marks: " + marks);

        if(marks >= 35){
            System.out.println("Result: Pass");
        } else {
            System.out.println("Result: Fail");
        }

        sc.close();
    }
}
