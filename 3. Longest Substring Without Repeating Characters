class Solution {
public:
    int lengthOfLongestSubstring(string s) {
        
        if(s.length()==0){return 0;}
        
        int result = 1;
        
        for(int i=0;i<s.length();i++){
           for(int j=i+1;j<s.length();j++){
               string temp(s,i,j-i+1);
               if(!isReapty(temp)){
                   if(result<(j-i+1)){result=j-i+1;}
                }
           } 
        }
        
        return result;
        
    }
    
    
  private:
    bool isReapty(string temp){
        bool result = false;
        for(int i=0;i<temp.length();i++){
            for(int j=i+1;j<temp.length();j++){
                if(temp[i]==temp[j]){result = true;break;}                        
            }
            
            if(result){break;}
        }
        return result;
    }
    
};
