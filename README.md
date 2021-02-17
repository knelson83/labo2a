# labo2a
/**
 *
 * @author kiwin
 */
public class MySearch {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        
        int [] inputArray = {13,16,3,2};
        
        for (int i = 0; i < inputArray.length; i++){
            if (inputArray[i] == 13){
                System.out.println("FOUND! Found at index" + i);
            }
        }
    }
    
