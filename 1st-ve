//{ Driver Code Starts
// Initial Template for Java
import java.io.*;
import java.util.*;
import java.util.HashMap;


// } Driver Code Ends
class Solution {

    // Function to find the first negative integer in every window of size k
    static List<Integer> FirstNegativeInteger(int arr[], int k) {
        
        List<Integer> list=new ArrayList<>();
             List<Integer> listx=new ArrayList<>();
        int j=0;
        int i=0;
        
        while(j<k){
            if(arr[j]<0){
                list.add(arr[j]);
                
            }
            j++;
            //making the 1st window
            
        }
        
        // storing the necessary result
        if(!list.isEmpty()){
            listx.add(list.get(0));
            
        }else{
            listx.add(0);
            
        }
        
        while(j<arr.length){
            if(arr[j]<0){
                list.add(arr[j]);
                
            }
            if( !list.isEmpty() && list.get(0).equals(arr[i])){
                list.remove(0);
                
            }
            i++;
            j++;
            //sliding the window logic
            
            
            
            //storing the necessary result
             if(!list.isEmpty()){
            listx.add(list.get(0));
            
        }else{
            listx.add(0);
            
        }
           
                
                
            }
            
            
            
            
            
            
        
        
        
        return listx;
        
        
  
        
        
    }
}

//{ Driver Code Starts.
public class Main {

    public static void main(String[] args) throws Exception {
        BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
        int t = Integer.parseInt(br.readLine());
        while (t-- > 0) {

            String line = br.readLine();
            String[] tokens = line.split(" ");

            // Create an ArrayList to store the integers
            ArrayList<Integer> array = new ArrayList<>();

            // Parse the tokens into integers and add to the array
            for (String token : tokens) {
                array.add(Integer.parseInt(token));
            }

            int[] arr = new int[array.size()];
            int idx = 0;
            for (int i : array) arr[idx++] = i;

            int k = Integer.parseInt(br.readLine());
            // Create Solution object and find closest sum
            Solution ob = new Solution();
            List<Integer> ans = ob.FirstNegativeInteger(arr, k);

            // Print the result as a space-separated string
            for (int num : ans) {
                System.out.print(num + " ");
            }
            System.out.println(); // New line after printing the results
            System.out.println("~");
        }
    }
}

// } Driver Code Ends
