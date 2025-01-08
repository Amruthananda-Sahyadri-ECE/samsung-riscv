 <summary>
    TASK 1 -DEVELOPMENT OF C PROGRAM
  </summary>
  ###step 1: fire up the terminal 
  bash 
  ### step 1: fire up the terminal 
  ```bash 
  vsduser@vsduser-VirtualBox:~$
  ```

  ###step 2: direction to home batch
  bash
  ### step 2: direction to home bash
  ```bash
  cd
  ```

  ###step 3: open leafpad bash
  bash
  ### step 3: open leafpad bash
  ```bash
  leafpad sum1ton.c &
  ```

  ###step 4: write the code
  c
  ### step 4: write the code
  ```c
  #include<stdio.h>
  int main(){
    int sum = 0, n = 86, i;
@@ -32,11 +36,13 @@ the project is based on the RISC V talent development program.
    }
    return 0;
}
  ```

  ###step 5: compile and run the code
  bash
  ### step 5: compile and run the code
  ```bash
  gcc sum1ton.c
  ./a.out
  ```
