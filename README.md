package двумер;

import java.util.Scanner;

/**
 *
 * @author LENOVO
 */
public class Двумер {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        
        
        System.out.println("Введите ширину массива: ");
        int m=sc.nextInt();
        System.out.println("Введите высоту массива: ");
        int n=sc.nextInt();
        int k=m*n;
        System.out.println("Введите "+ k + " элементов массива: ");
        int i;
        int j;
         int[][] mas = new int[n][m];
        for ( i=0; i<n; i++){
         for( j=0; j<m; j++){
          mas[i][j]=sc.nextInt();
         }
        }
         
        System.out.println("Ваши элементы массива: ");
        for ( i=0; i<mas.length; i++){
         for( j=0; j<mas[i].length; j++){
            
             System.out.print(mas[i][j]+ "\t");
         }
            System.out.println();
        }
        }
    
        
        
    }
  
