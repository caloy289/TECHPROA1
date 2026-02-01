class Person {
    private String name;
    private int age;

    public void setName(String name) {
        this.name = name;
    }

    public void setAge(int age) {
        if (age > 0) {
        this.age = age;
        } else {
        	this.age = 0;
        }
    }

    public String getName() {
        return name;
    }

    public int getAge() {
        return age;
    }
}

class Student extends Person {
    private String course;

    public void setCourse(String course) {
        this.course = course;
    }

    public String getCourse() {
        return course;
    }

   
    public void displayInfo() {
        System.out.println("---------- STUDENT INFORMATION ----------");
        System.out.println("Student Name: " + getName());
        System.out.println("Student Age: " + getAge());
        System.out.println("Course: " + getCourse());
        System.out.println("-----------------------------------------");
    }
}


public class Main {
    public static void main(String[] args) {
        
        Student s = new Student();


        s.setName("ABUD");
        s.setAge(61);


        s.setCourse("ICT");


        s.displayInfo();
    }
}
