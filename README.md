# Set up a virtual environment
 Set up a virtual environment

The objective of this tutorial is to:
* Lauch an AWS instance,
* Check for Python,
* Execute a Python script from that instance.


 # Choice of the instance

![Légende](AMI_choice.PNG)

## Connection information & IP address of the instance

![Légende](Info_instance.PNG)

![Légende](Publi_IP_instancPNG.PNG)

## Connection to the instance using ubuntu

![Légende](Connection_instance_ubuntu.PNG)

## Installation of Python on the Instance

* Update the list of available files into APT present into the configuration file.

![Légende](Update.PNG)

* Installation of Python3

![Légende](Installation_python3.PNG)

* Create a text file using the editor vi

![Légende](Vi_editor.PNG)

type "i" to include code. For example Print("Hello Brieuc").

![Légende](Fichier_python_print.PNG)
![Légende](File python created.PNG)

Check that we are able to run the Python file.

![Légende](Hello.PNG)

## Connection on Jupyter (user friendly environnement) from the Instance

Still by using Ubuntu.

![Légende](Install_Jupiter.PNG)
![Légende](Jupiter.PNG)

Configure to have access to it anytime type the following command:
**nohup jupyter notebook --ip=0.0.0.0&**

Getting information about the connection:

![Légende](Info_nohup.PNG)

For closing the Jupyter notebook, you just need to type: **close jupyter notebook**

# Create virtual environment

You have two possibilities: using **Conda** or **Pew**

## By using Conda

![Légende](Conda.PNG)

![Légende](Env_conda_create.PNG)

## By using Pew

* Installing Pew
![Légende](Install_pew.PNG)

* Create a specific Kernel
![Légende](Install_Kernel_conda.PNG)

* Check the creation of the new environment
![Légende](Env_BrieucEnv.PNG)
