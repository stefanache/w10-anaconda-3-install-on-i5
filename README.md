Procedure: Install Anaconda3 

OS: Windows 10(W10 Pro)

CPU: Intel(i5) on 64 bits

Anaconda is a free, easy-to-install package manager, environment manager and Python distribution with a collection of 1,000+ open source packages with free community support. Anaconda is platform-agnostic, so you can use it whether you are on Windows, macOS or Linux.



I write this procedure for people which intend to use Anaconda3 on your personal computer/laptop
(which finally will create one Python environment for Machine [or Deep] Learning).

In my opinion, if intend to work with Anaconda3(which contain the 'conda.exe' as main tool) you can before 
uninstall any version of Python[s] which have installed in the past(is most important note!).

For that, you can use before to uninstall any version of local Python program using the following way to find 
the programs uninstall management from Winsows 10 Pro(W10 Pro):

    Control Panel -> Programs (the 'Uninstall  a program' option)

Manual procedure of installment for Anaconda3 consist in the folowing 3-steps:

1) check your hardware(HW) and software(SW) context(to know if apply this manual pocedure):

  go to taskbar on second icon(windows search) from your operation system(Windows 10 Pro) and type the word 
  
  				   system
   
  and then choice to click on the 'System Information" apllication to check to view if have the following context:
 
  - Operation System(OS Name):   Microsoft(MS) Windows 10 Pro
  
  ...
  
  -System Type: x64 based PC
  
  ...
  
  -Processor:                    Intel(R)...i5...CPU ... 64 bits...
  
  ...
  
  -Installed Physical Memory(RAM):  8.00 GB            (or more:)
  
  ...
  
  
  Remark:
  
  	 In fact I worked with laptop  which have:
  
				...
				
				System Model: Inspiron 5567
				
				...
				
          but I think work on any(or many) system with Windows 64-Bit.
		  
2) go to any browser(I prefer Chrome but can use any browser) and write this address URL:
         https://www.anaconda.com/download/
	 
   and click on(select) the
   
   		'64-Bit Graphical Installer(now it have and show 614.3 MB)'
	
   under 
   
   		'Python 3.7 version *'(now refer to Python 3.7.1)
	
   then waiting to finish the download.
   After that  open your directory 
   
        c:\Downloads
	
   to see if the download of file named:
   
         Anaconda3-2018.12-Windows-x86_64.exe
	 
   is finished.
	
3) Finally, click on this file 
		Anaconda3...-Windows-x86_64.exe 
   from 
   		c:\Downloads 
   directory to start the Anaconda3's installer.
   
   Accept all and then click 'Next' to 'Finish' the installation.
   
   Please 
   
   		Not modify anythink option on during installation!
		
		
   Normally the directory which contain entire Anaconda3 64 bits will be :
   
      C:\Users\{your username}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Anaconda3 (64-bit)

The Anaconda3 have two main components:

    Anaconda Navigator and
    
    Anaconda Prompt

Remarks:

Anaconda Navigator is one GUI=graphical user interface(or interaction) and 

Anaconda Prompt(my preference) is one client user interface=CLI.


The Anaconda Prompt in fact is one terminal window which show you one simple shell prompt like :

    (base) C:\Users\{your username} > 
    
the (base) is name for your current(default) environment and then follow

the current path where is now located the your user's prompt:
    C:\Users\{your username}
    
 The propmpt for user CLI is '>' where you click to enter your commands for Anaconda3.
 
 
 For example you can type this command to know which 'conda' version have you installed for now:
 
    (base) C:\Users\{your username}> conda -V
    
 and the response for mine is 
                                     conda 4.5.12
				    
 or if want to know the Anaconda3 version(in fact which versions have all components from Anaconda3) then type:
 
    (base) C:\Users\{your username}> conda list anaconda
 and the response for mine is :
 					
					# Name                    Version                   Build  Channel
					
					anaconda                  custom                   py37_0
					anaconda-client           1.7.1                      py_0    conda-forge
					anaconda-navigator        1.9.6                    py37_0
					anaconda-project          0.8.2                      py_1    conda-forge
					
The conda.exe program(which in fact is similar with wellknown 'pip' which manage the installment of pachages for any python) 
can show which packages are already in Anaconda3's enviroment(like 'base'):

    (base) C:\Users\{your username}> conda list
    
which show in mine case this

# Name                    Version                   Build  Channel
....
python                    3.7.1             hc182675_1000    conda-forge
...

Remark:
        The channel is one repository/residance/location/server where the 'conda' find the software
	(like anaconda-clent,navigator,project component,  python package...) when it install in 'base' environment.
	I can create with 'conda' and other specific environmet for my application wich my python-application depend.
	For example I can create one specific environment 'TF-CPU-KS-Py36' named on Python 3.6 based 
	for my application(CPU instead of GPU) which work in particular with Keras (TensorFlow based).
	
The docummentation for Anaconda3 can be find at
  	https://docs.anaconda.com/

The  conda command reference consult  the document at
	https://conda.io/docs/commands.html

  
  That is all for now!
  Thanks.
  
  # w10-anaconda-3-install-on-i5 
