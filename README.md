# checking-whether-a-string-contains-only-digits
# Activity 1- Test your Java Programming Skills
 
 
public class Example {
    public static void main(String[] args){
        String str = "6347842345";
        boolean result = str.matches("[0-9]+");
        System.out.println("Original String : " + str);
        System.out.println("Does string contain only Digits? : " + result);
    }
}
