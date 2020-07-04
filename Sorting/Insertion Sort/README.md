# Implementation of Insertion Sort

Pseudo-Code

INSERTION-SORT(A)
- for j=2 to A.length
- key=A[j]
    
    i=j-1
    
    While i>0 and A[i]>key:
    
         A[i+1]=A[i]
        
          i=i-1
    
    A[i+1]=key
