# Comment-Remover-in-C-Lang
 C/C++ and Java comment eliminator writern in C-language

 step 1:
 
 ![](https://github.com/sutharp777/Comment-detector-and-Remover-in-C-Lang/blob/master/run.png)
 
 # in.c
 
    /// this is c program to remove the comment
    #include<stdio.h>
    /* start of main() func
       this is m.. com
    */
    int main(){	// start
	      cout<<"Hello World\n";
	      return 0;
	      // done 
    }
    // thank you
    
    
  # out.c
  
    #include<stdio.h>
    int main(){
       cout<<"Hello World\n";
	      return 0;
	   }
