# TypeCasting

► Type casting is the conversion of one type to anther type

#### 2 Types Of Type Casting
i. implicit type conversion

Implicit type casting:

This is from low to high conversion. The compiler does this implicit conversion automatically. Basically, low can fit into high easily.

ii. explicit type conversion

Explicit type casting:

This is from high to low. The compiler does not do the conversion automatically. The developers do the conversion instead.

Note:

int = 4 bytes

double = 8 bytes

char = 2 bytes


Example 1-

class test{

  public static void main(String[] args){                     

    double d = 10;

    System.out.println(d);
    
  }
  
}

Output - 10.0

10 is integer, but it gets converted to a double number. That is done by the compiler automatically, it will convert automatically.

Example 2-

class test{

  public static void main(String[] args){                     

    int data = 'a';

    System.out.println(data);
    
  }
  
}

Output- 97

Lowercase 'a' is equal to 97 according to ASCII value.

Example 3-

class test{

  public static void main(String[] args){                     

   int x = 10.5;

    System.out.println(x);
    
  }
  
}
Output - 

incompatible types: possible lossy conversion from double to int.

To solve the error we have to type cast by using parantheses, so we can match the data type.

Ex:

class Test{

  public static void main(String[] args){

    int x = (int)10.5;

    Syste.out.println(x);
    
  }
  
}




