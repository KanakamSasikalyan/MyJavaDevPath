## Method Overriding

Method overriding is an object-oriented programming feature, in which declaring the method in the subclass which is already present in the parent class/ super-class is called as method overriding. The child class can give its own implementation without impacting the parent class method.

### Advantages of the Method Overriding
The main advantage of the method overriding is to maintain the reusability of the code. The subclass can give its own implementation with the same signature of the method which is already defined in the super class.

### Rules of method overriding in Java
- Argument list: The argument list of overriding method (method of child class) must match the Overridden method(the method of parent class). The data types of the arguments and their sequence should exactly match.
- Access Modifier of the overriding method (method of subclass) cannot be more restrictive than the overridden method of parent class. For e.g. if the Access Modifier of parent class method is public then the overriding method (child class method ) cannot have private, protected and default Access modifier,because all of these three access modifiers are more restrictive than public.
- For e.g. This is not allowed as child class disp method is more restrictive(protected) than base class(public)