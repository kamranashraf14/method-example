# method-example
same thing but two way
method 1

 public class Main {
    public static void main(String[] args) {
     add( 7,3);
  }
  
  static int add( int a,int b){
    int sum = a + b;
    System.out.println(sum);
    return sum;
    
  }
}
..........................................................................
method 2
public class Main {
    public static void main(String[] args) {
     int ans = add( 7,3);
     
     System.out.println(ans);
  }
  
  static int add( int a,int b){
    int sum = a + b;
    
    return sum;
    
  }
}
