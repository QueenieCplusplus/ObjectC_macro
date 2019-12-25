# bjectC_macro
巨集和標頭檔一樣，屬於預先編譯處理。

符號表示

         #define KeyWord string
         
有參數時的表示
 
         #define KeyWord(Param) string
         
取消巨集 

         #undef 巨集名稱
         
實作範例

      #import <Foundation/Foundation.h>
      #define PI 3.14159
      #define V(s, h), s*h
      
      int main()
      {
      
        @autoreleasepool {
        
           //...
        
        }     
      
        return 0;
        
      }
             
 
         
         
         
         

