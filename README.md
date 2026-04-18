# Parichay-Yadav-JavaStrings
// Name: Parichay Yadav

public class StringPractice {
    public static void main(String[] args) {

        // Declaring two string variables
        String str1 = "Hello";
        String str2 = "World";

        // 1. length()
        System.out.println("Length of str1: " + str1.length());

        // 2. concat()
        System.out.println("Concatenation: " + str1.concat(" " + str2));

        // 3. toUpperCase() and toLowerCase()
        System.out.println("Uppercase str1: " + str1.toUpperCase());
        System.out.println("Lowercase str2: " + str2.toLowerCase());

        // 4. substring()
        System.out.println("Substring of str1 (1 to 4): " + str1.substring(1, 4));

        // 5. equals()
        System.out.println("Are str1 and str2 equal? " + str1.equals(str2));

        // 6. equalsIgnoreCase()
        System.out.println("Are 'hello' and str1 equal (ignore case)? " + str1.equalsIgnoreCase("hello"));

        // 7. replace()
        System.out.println("Replace 'l' with 'x' in str1: " + str1.replace('l', 'x'));

        // 8. charAt()
        System.out.println("Character at index 2 in str1: " + str1.charAt(2));
    }
}
this is my firast githuib project
