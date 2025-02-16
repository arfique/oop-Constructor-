//Date (2/6/25)

1.

public class SumNameExample {

    public static void sumName(int num1, int num2, double d1, double d2, String s1, String s2) {
        int intSum = num1 + num2;
        double doubleSum = d1 + d2;
        String concatenatedStr = s1 + s2;

        System.out.println("Integers sum: " + intSum);
        System.out.println("Doubles sum: " + doubleSum);
        System.out.println("Concatenated string: " + concatenatedStr);
    }

    public static void main(String[] args) {
        sumName(7, 5, 10.5, 2.3, "Ijaj", " Hakim");
    }
}


2.


public class Main {
    public static void main(String[] args) {
        
        double height = 10.0; 
        double width = 5.0; 
        double radius = 3.0;  

        double areaRectangle = calculateRectangleArea(height, width);
        double areaCircle = calculateCircleArea(radius);
        
        display("Area of the rectangle: ", areaRectangle);
        display("Area of the circle: ", areaCircle);
    }

    public static double calculateRectangleArea(double height, double width) {
        return height * width;
    }

    public static double calculateCircleArea(double radius) {
        return Math.PI * radius * radius;
    }

    public static void display(String description, double value) {
        System.out.println(description + value);
    }
}



3.  


public class Main {
         double height;
         double width;
         double radius;
     
    // Constructor for rectangle
    public Main(double height, double width, double radius) {
        this.height = height;
        this.width = width;
        this.radius= radius;
    }
     public  double area(double height, double width) {
       
        return height * width;
    }

    public double area(double radius) {
        return 3.1416 * radius * radius;
    }
    public static void main(String[] args) {
        Main obj = new Main(10.0, 5.0, 6.7);
        double area1= obj.area(10.5, 5.0);
        double area2 = obj.area(2.2);
        
        System.out.println(area1+ " "+area2);

    }

   
    }
