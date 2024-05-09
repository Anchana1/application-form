# application-form
-------------------------java----------------------------------------
public class Appform {
    String name;
    int age;
    float mark;

    public static void setvalue(String name, int age, int mark) {
        this.name = name;
        this.age = age;
        this.mark = mark;
    }

    public static void display() {
        System.out.println("name=" + name);
        System.out.println("age=" + age);
        System.out.println("mark=" + mark);
    }

    public class Student {
        public static void main(String[] args) {
            Appform obj = new Appform();
            obj.setvalue(String"Anchana",int 5,int 555);
            obj.display();

        }
    }

}
