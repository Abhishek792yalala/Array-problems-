# Array-problems-

Array problems

class Java{

    //Reversing an array

    public static void main(String... args){

        intOverloading

// Method overloading problem:

class Code {

    public int m1(int a, int b) {

        System.out.println("concatenation of a and b is: " + a + b);

        return a + b;

    }

    public float m1(float a, float b) {

        System.out.println("concatenation of c,d and f is: " + a+b);

        return a+b;

    }

    //Same signature of method with different data types is allowed, it is the method overloading concept

    public static void main(String... args) {

        System.out.println("Welcome to java programming");

        Code cc = new Code();

        cc.m1(1, 2);

        cc.m1(1,  3);

    }

}

/*

Welcome to java programming

concatenation of a and b is: 12

concatenation of a and b is: 13

 */ [] a={1,2,3,4};

        for(int i=a.length;i>0;i--){

            System.out.println(i);

            }

        }

    }

        4

        3

        2

        1

class Java{

    //To search the number in an array

    public static void main(String... args){

        System.out.println("Welcome to java programming");

        int arr[]={1,2,3,4}; int num=1;

        for(int element:arr){

            if(num==element){

               System.out.println("Number is in array");

                break;

            }

            else{

                System.out.println("Number is not in array");

                break;

            }

        }

    }

}

    Welcome to java programming

    Number is in array

//To sort without using temp variable

class Java{

    public static void main(String... aaa) {

        int a=1, b=3;

        a=a+b;

        b=a-b;

        a=a-b;

        System.out.println("The sorted value of a is : "+ a);

        System.out.println("The sorted value of b is : "+  b);

    }

}

//To sort an array

class Java{

    public static void main(String... aaa) {

      int a[]=new int[3];

      a=new int[]{7,6,5,4,3,2,1};

      System.out.println("Original array");

      for(int x: a){

          System.out.println(x);

      }

      System.out.println("Sorted array");

      int max=a[0];

      for(int i=0;i< a.length;i++){

          for(int j=i+1;j<a.length;j++){

          if(a[i]>a[j]){

              max=a[j];

              a[j]=a[i];

              a[i]=max;

          }

          }

          System.out.println(a[i]);

      }

    }

}

/*

Original array

7

6

5

4

3

2

1

Sorted array

1

2

3

4

5

6

7

 */
