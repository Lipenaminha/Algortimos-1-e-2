using System;

class Program {
  public static void Main (string[] args) {

    ContarRegressivo(20);
    
  }

  public static void ContarRegressivo(int fim)
  {
    if(fim != 0){
      Console.WriteLine(fim);
      ContarRegressivo(fim -1);
    }
    else {
      Console.WriteLine(0);
      Console.WriteLine("==fim==");
    }
    
  }
}
