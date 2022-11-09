### Hi there 👋

```java

public class Developer {

    private String name;
    private String pronouns;
    private String[] interests;

   public Developer(String name, String pronouns, String[] interests) {
      this.name = name;
      this.pronouns = pronouns;
      this.interests = interests;
   }
   
   public void sayHello() {
      System.out.println("Hi! My name is " + name + " (" + pronouns + "), and I like " + Arrays.toString(interests));
   }

}


public static void main(String[] args) {
   Developer me = new Developer("Tommy", "he/him", new String[]{"Java", "NodeJS", "Python", "HTML/CSS/JS", "coding in general ;)"});
   me.sayHello();
}

```
