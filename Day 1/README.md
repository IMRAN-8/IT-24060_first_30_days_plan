Example 1: The Car Class
---
```java
class Car {
    String brand;
    int year;
    void displayInfo() {
        System.out.println("Brand: " + brand + ", Year: " + year);
    }
}

public class Main {
    public static void main(String[] args) {
        Car myCar = new Car();
        myCar.brand = "BMW";
        myCar.year = 2026;
         myCar.displayInfo(); 
    }
}
```
---
Example 2: The SmartPhone Class
---
```java
class SmartPhone {
    String model;
    int storageGB;
}

public class Main {
    public static void main(String[] args) {
        SmartPhone phone1 = new SmartPhone();
        phone1.model = "iPhone 17";
        phone1.storageGB = 512;
        SmartPhone phone2 = new SmartPhone();
        phone2.model = "Samsung S26";
        phone2.storageGB = 512;
        System.out.println("Phone 1: " + phone1.model + " with " + phone1.storageGB + "GB");
        System.out.println("Phone 2: " + phone2.model + " with " + phone2.storageGB + "GB");
    }
}
```
