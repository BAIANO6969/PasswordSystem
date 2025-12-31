import java.util.Scanner;

public class PasswordSystem {

    import java.util.Scanner;

    public class PasswordSystem {
        public static void main(String[] args) {
            Scanner scanner = new Scanner(System.in);
            String password;
            boolean valid;

            do {
                System.out.println("Enter your password: ");
                password = scanner.nextLine();

                //checks if it contains only letters and numbers
                if (password.matches("[a-zA-Z0-9]+") && password.length() >=6 && password.length() <=100) {
                    valid = true;
                    System.out.println("Valid password entered: " + password);
                } else {
                    valid = false;
                    System.out.println("Invalid password! Use only letters and numbers (minimum 6 characters).");

                }
            }while (!valid);

            scanner.close();
        }
    }

}

