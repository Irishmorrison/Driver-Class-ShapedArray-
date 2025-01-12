# Driver-Class-ShapedArray-
// ShapedArray.java
public class ShapedArray {
    public static void main(String[] args) {
        Shape[] shapeArray = new Shape[3];
        shapeArray[0] = new Sphere(5);
        shapeArray[1] = new Cylinder(3, 7);
        shapeArray[2] = new Cone(4, 9);

        for (Shape shape : shapeArray) {
            System.out.println(shape);
        }
    }
}
