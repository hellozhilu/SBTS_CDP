# SBTS_CDP
Source code for the article "Solution-based tabu search for the capacitated dispersion problem"

1. For the source code, you can specify the parameters to match your needs when you execute the code. The code was tested on a computer under Linux operating system. If you have any questions feel free to contact me (Zhi Lu: zhilusix@gmail.com).     
   
   ```
   g++ ./src/main.cpp ./src/common_func.cpp ./src/local_search.cpp -o ./CDP -O3
   ```
   ```
   CDP.exe ./CDP_Instances/CDP_Instances_b02/GKD-b_11_n50_b02_m5.txt 147.2 300 400 500
   ```
   among them,  
   ```
   CDP.exe              //binary code
   ./CDP_Instances/CDP_Instances_b02/GKD-b_11_n50_b02_m5.txt //input instance file
   147.2                //best-known result for current instance (GKD-b_11_n50_b02_m5.txt)
   300                  //parameter in the first hash function h1(M)
   400                  //parameter in the second hash function h2(M)
   500                  //parameter in the third hash function h3(M)
   ```
  
2. Please make sure that the following paper is cited if you use the code in your research.    
   Lu, Z., Martínez-Gavara, A., Hao, J. K., & Lai, X. (2023). Solution-based tabu search for the capacitated dispersion problem. Expert Systems with Applications, 223, 119856.

3. The source code is distributed for academic purposes only.    
   If you wish to use it for commercial applications, please contact the authors (Zhi Lu: zhilusix@gmail.com, Anna Martı́nez-Gavara: gavara@uv.es).  
