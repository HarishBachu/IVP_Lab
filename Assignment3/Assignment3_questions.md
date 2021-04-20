# Assignment 3

1. Write and proof  the various properties related to 2D Discrete Fourier  Transform.

( Note: submit scanned  copy of solution in single pdf file)

2.  a. Write python from scratch for computing 2D DFT{X(k,l)} of the following 2D array <br>
        i.) x(m,n) = np.array([[1, 0],[2, 1]])                  
        ii.) x(m,n) = np.array([[1,2, 3,4], [5, 6, 7, 8], [9,10,11,12], [13,14,15,16]])

    b. Verify the results of part a. by analytical solution method ( i.e. pen and paper based solution)

3.  a. Write python from scratch for 2D Circular convolution using  Doubly Block Circulant matrices method between <br>input=np.array([[1,2,3],[4,5,6],[7,8,9]]) and <br>filter=np.array([[1,2,1],[0,0,0],[-1,-2,-1]])

    b. verify the result of part a. by  analytical solution method ( i.e. pen and paper-based solution)

4.  a. Write python from scratch for 2D DCT   transform  on the following matrix:<br>
    i.)  f(m.n) = [ 90, 100 ; 100,  175]  
    ii.) f(m.n) = [ 10, 20,  30; 40  50 60  ; 70 80, 90; 100, 110, 120; 130 140, 150]  
    iii.)   f(m.n)= monalisa.tif
    and also comment on energy compaction property  of DCT                              

    b. Write python from scratch for 2D IDCT   transform  and reconstruct f(m,n) from  part a.



