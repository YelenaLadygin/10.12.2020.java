Task 1:

    Scanner s = new Scanner(System.in);
   System.out.println(" Enter two int numbers :");
    int a = s.nextInt();
    int b = s.nextInt();
      if (a > b)
         System.out.printf(" %d > % d" , a, b);
      else if  ( a < b)
        System.out.printf(" %d < % d" , a, b);
     else
        System.out.printf(" %d = % d" , a, b);
Task 2 :

    int x = 5;
      while (x <= 10) {
        System.out.println(x);
        x++;
    }
    
    Task 3 : 
    
    Scanner s = new Scanner(System.in);
    System.out.println(" Enter the int number :");
    int num = s.nextInt();
        while (num != 100) {
        System.out.println(" Try again");
        num = s.nextInt();
    }
    System.out.printf(" Very nice. The number is %d", num)
}

Etgar 1: 

    int x = 4;
      while (x <= 100) {
        System.out.println(x);
         x+=2;
   }
   
   Etgar 2 : 
   
    Scanner s = new Scanner(System.in);
    System.out.println(" Enter the two int numbers :");
    int a = s.nextInt();
    int b = s.nextInt();
       while (a!= b) {
          System.out.println(" Try again");
          a = s.nextInt();
          b = s.nextInt();
    }
      System.out.printf(" Very nice. The number is %d = %d", a,b);
