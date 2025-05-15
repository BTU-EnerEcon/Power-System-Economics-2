# PSE2
Hello Students, this read me file will guide you in setting up mini conda  and Pyomo in your PC.There are mainly 3 steps in this process:
  * Setting up the environment using miniconda
  * Installing the necessary packages
  * Running the IDE
------------------------------------------------------------------------------------------------------------------------------

## **Setting up the environment using miniconda** 

It is convenient to setup an environment using miniconda , to avoid dependency conflicts.
  * For this we first download miniconda from the website: https://www.anaconda.com/download/  .You can either create an 
    account and download or skip registration and download. Please select the recommended settings while installation.
  * After installing miniconda, press windows and search for 'anaconda prompt'. Click on it and the prompt window opens up.

for detailed tutorial check out the following youtube video: https://www.youtube.com/watch?v=oHHbsMfyNR4 .

------------------------------------------------------------------------------------------------------------------------------
## **Installing the necessary packages**

The second step is installing the packages. I have included Spyder IDE , but if you have individual preference you can install that IDE. To start with this step:

   * Type the following code in the anaconda prompt

 ```
 conda create --name pse -c conda-forge python=3.10 pyomo spyder glpk
``` 
* The environment will be created and you can activate it by typing
```
conda activate pse
```
* The environment will be activated and the name of the environment can be seen in the beginning of the command line.

 Any missing packages can be installed dynamically.

 ---------------------------------------------------------------------------------------------------------------------------

 ## Running the IDE

 Now that the environment is activated we can run the IDE by typing the IDE name as shown. Since i prefer spyder i typed the following and pressed enter

```
spyder
```

The spyder IDE will open up and we can enter the code there.

----------------------------------------------------------------------------------------------------------------------------
