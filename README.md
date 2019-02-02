# Cars
Cars
A dataset of Cars is provided in a file (input.txt). The file has the three fields for each car: Name, Origin, Horsepower. Given this file and given a number N, and an origin O, print N cars that have horsepower greater than the average horsepower of all the cars from origin O. Note that the average horsepower should be computed from the cars of the given origin and not the whole dataset. The path to the dataset and the values of N and O will be passed as arguments to the program on command line.<br><br>


For example, in the dataset below:<br><br>
	

Chevrolet Chevelle Malibu,130.0,US<br>	
Buick Skylark 320,165.0,US<br>
Plymouth Satellite,150.0,US<br>
Volkswagen 1131 Deluxe Sedan,46.0,Europe<br>
Peugeot 504,87.0,Europe<br>
Audi 100 LS,90.0,Europe<br><br>


* Given N=1 and O=US, the output should be:<br>
  Buick Skylark 320,165.0,US<br>

![1](https://user-images.githubusercontent.com/25060937/52166625-bda57d00-2735-11e9-9ae2-719910542638.PNG)


* Given N=2 and O=US, the output should be:<br>	
  Buick Skylark 320,165.0,US<br>
  Plymouth Satellite,150.0,US<br>

![2](https://user-images.githubusercontent.com/25060937/52166633-d0b84d00-2735-11e9-8d1a-d96792b6e63d.PNG)


* Given N=3 and O=US, the output should be:<br>
  Buick Skylark 320,165.0,US<br>
  Plymouth Satellite,150.0,US<br>

![3](https://user-images.githubusercontent.com/25060937/52166645-e7f73a80-2735-11e9-81ab-72c37b4396da.PNG)


* Similarly,<br>
* Given N=1 and O=Europe, the output should be:<br>
  Audi 100 LS,90.0,Europe<br>

![4](https://user-images.githubusercontent.com/25060937/52166654-f7768380-2735-11e9-89e9-87c7ddcd1313.PNG)


* Given N=2 and O=Europe, the output should be:<br>
  Peugeot 504,87.0,Europe<br>
  Audi 100 LS,90.0,Europe<br>

![5](https://user-images.githubusercontent.com/25060937/52166655-078e6300-2736-11e9-8e3c-20d97d2a4dd2.PNG)

* Given N=3 and O=Europe, the output should be:<br>	
  Peugeot 504,87.0,Europe<br>
  Audi 100 LS,90.0,Europe<br>

![6](https://user-images.githubusercontent.com/25060937/52166659-1d038d00-2736-11e9-9307-7390943db5b6.PNG)

# Input.txt<br>
![input](https://user-images.githubusercontent.com/25060937/52166807-2857b800-2738-11e9-9cea-7a355a47b790.PNG)
<br><br>
# Temp.txt<br>
![temp](https://user-images.githubusercontent.com/25060937/52166830-68b73600-2738-11e9-87b8-70ecb2e2547a.PNG)
<br><br>
# Output.txt<br>
![output](https://user-images.githubusercontent.com/25060937/52166829-67860900-2738-11e9-8040-616f992036d0.PNG)
<br><br>

