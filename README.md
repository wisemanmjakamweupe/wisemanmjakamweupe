- 👋 Hi, I’m @wisemanmjakamweupe
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
import java.util.main
<!---
wisemanmjakamweupe/wisemanmjakamweupe is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import java .util.Scanner;


public class HotelLogin {
    private static final String USERNAME = "admin";
    private static final String PASSWORD = "password";

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Welcome to the Hotel Management System!");
        System.out.println("Please enter your username and password to login.");

        System.out.print("Username: ");
    scanner    String usernameInput = scanner.nextLine();

        System.out.print("Password: ");
        String passwordInput = scanner.nextLine();

        if (login(usernameInput, passwordInput)) {
            System.out.println("Login successful. Welcome, " + USERNAME + "!");
            // Add your hotel management functionality here
        } else {
            System.out.println("Invalid username or password. Please try again.");
        }
    }

    private static boolean login(String username, String password) {
        return username.equals(USERNAME) && password.equals(PASSWORD);
    }
}


    
