# Simple video output test circuits

The first test is the basic counter which
generates the synchronization pulse and the
display enable signal.

![synch circuit test](../gerados/testeTemporiza.svg)

Then two synch circuits are connected together
and their counts are used to generate a color
pattern.

![color pattern circuit](../gerados/testeCoresVGA.svg)

![color pattern](../gerados/testeCoresVGA.png)

A pattern of vertical and horizontal lines is
used to test alignment.

![squares pattern circuit](../gerados/testeQuadradosVGA.svg)

![squares pattern](../gerados/testeQuadradosVGA.png)

A simple 8x16 character ROM has its output serialized.

![char ROM circuit](../gerados/testeTextoVGA.svg)

![char ROM output](../gerados/testeTextoVGA.png)

First implementation of a palette circuit using two
rectangle generators.

![rectangle circuit](../gerados/testeRetangulosVGA.svg)

![rectangle output](../gerados/testeRetangulosVGA.png)
