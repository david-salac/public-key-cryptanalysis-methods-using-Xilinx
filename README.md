# The acceleration of public-key cryptanalysis methods using Xilinx Zynq-7000
The Xilinx Zynq-7000 SoC provides new possibilities
for increase of efficiency of cryptanalysis methods for public–
key systems such as RSA or Diffie–Hellman key exchange algorithm. 
These cryptosystems are based on the discrete logarithm
and integer factorization problem. After brief introduction to
numerical methods for solving of these problems there is an
introduction to the distributed system that aims to solving of
these problems. Distributed system consists of master nod that
manage the distribution of the tasks and slave nods that computes
one of the most time consuming part of the selected numerical
methods called sieving. Afterward the slave nod is designed on
Xilinx Zynq-7000 SoC consists of ARM processor for analyzing
of the problem and some custom IP cores running on FPGA
for increasing of the efficiency of algorithm. The capabilities of
distributed system is also measured and analyzed afterward.

## Rest of the article
The whole article is in the file SALAC_conf.pdf
