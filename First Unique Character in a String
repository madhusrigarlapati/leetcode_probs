import java.util.Map.Entry;
class Solution {
    public int firstUniqChar(String s) {
        int k=0;
         HashMap<Character,Integer> a=new HashMap<>();
        for(int i=0;i<s.length();i++){
            if(a.containsKey(s.charAt(i))){
                int b=a.get(s.charAt(i));
                a.put(s.charAt(i),b+1);
                
            }
            else{
                a.put(s.charAt(i),1);
            }
        }
        int c=0;
        for(int i=0;i<s.length();i++) {
            if(a.get(s.charAt(i)) == 1) {
                c=i;
                k++;
                break;
            }
        }
        if(k>0){
            return c;
        }
        else{
            return -1;
        }
    }
}
