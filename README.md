# SumOfArray
public class SumOfArray {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
        int[]arr = new int[] {3,5,7,8,9};
        int sum = 0;
             
            for(int i=0; i<arr.length; i++){
          sum=sum+arr[i];
            }
            System.out.println("Sum of all the elements of an array:"+sum);
            
            }
    } 
