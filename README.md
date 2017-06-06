# new-test
public class test{
  public void bubble(int a[]){
    for(int i=1;i<a.length;i++){
      for(int j=0;j<a.length;j++){
        if(a[j]>a[i]){
          int temp=a[j];
          a[j]=a[i];
          a[i]=temp;
        }
      }
    }
    for(int i=0;i<a.length;i++){
      System.out.print(a[i]+",");
    }
  }
  
  public static void main(String[] args){
    int a[]={45,77,41,2,5,69,40,21,33};
    test t=new test();
    t.bubble(a);
  }
}

