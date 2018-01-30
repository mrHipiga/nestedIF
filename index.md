/**
 * @(#)nestedIF.java
 *
 *
 * @author 
 * @version 1.00 2018/1/9
 */
import javax.swing.JOptionPane;

public class nestedIF {
    public static void main(String[] args) {
   				int value;
   				
   	value = Integer.parseInt(JOptionPane.showInputDialog("Enter a Value"));	
   		
   	if ((value >= 0) && (value <= 10))
   		JOptionPane.showMessageDialog(null, "POOR");
   		
   		else if ((value >= 11) && (value <= 20))
    		JOptionPane.showMessageDialog(null, "AVERAGE");
   	
   			else if ((value >= 21) && (value <= 30))
    		    JOptionPane.showMessageDialog(null, "EXCELLENT");
    		else
     		    JOptionPane.showMessageDialog(null, "INVALID INPUT");
   
   
    }
}
