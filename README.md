I write this procedure for people wich intend to use Anaconda3 on your personal computers/laptops
wich finnaly will create one Python environment for Deep or Machine Learning.

In my opinion if intent to work with Anaconda 3(whic contain the conda as main tool as any anconda version)
you must to uninstall any Python wich have installed in the past.
For that you can use: 
    Control Panel -> Programs (the 'Uninstall  a program' option)

Muanual procedure of installment for Anaconda 3 consist in the folowing steps:
1) check your hardware(HW) and software(SW) context:
  go to taskbar on second icon(windows search) from your operation system(Windows 10 Pro) and type control
  and choice system information and check if have
  - Operation System(OS Name): Miscosoft(MS) Windows 10 Pro
  ...
  -System Type: x64 based PC
  ...
  -Processor: Intel(R)...(i5)
  ...
  -Installed Psical Memory(RAM): 8.00 GB (or more)
  ...
  
  Remark: In fact I have this experiment on my my laptop :
				...
				System Model: Inspiron 5567
				...
		  but I think work on many(or any) machines with Windowns 64-Bit
		  
2) go to any browser(I prefer Chrome but can be any browser) and write this address URL:
         https://www.anaconda.com/download/
   and click on(select) the   64-Bit Graphical Installer(now it have 614.3 MB)
   under Python 3.7 version *(now refer to Python 3.7.1)
   Waiting and open your c:\Downloads system to see that you download the file 
     Anaconda3-2018.12-Windows-x86_64.exe
3) Click on this file Anaconda3...-x86_64.exe to start the your installer.
   Accept all and then click next to finish the installment.
   Not modify anythink.
   Normally the directory wich contain entire Anaconda3 64 bits will be :
      C:\Users\{your username}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Anaconda3 (64-bit)

The Anaconda3 have two main components:
    Anaconda Navigator
    Anaconda Prompt

Remarks:

Anaconda Navigator is for GUI=graphical user interface(or interaction) and Anaconda Prompt(my preference) is for client user interface=CLI.
The Anaconda Prompt in fact is one terminal window wich show you one simple shell prompt like 
    (base) C:\Users\{your username}>
(base) is name for your current environment and then follow the current path wher is now loccated your user=prompt: C:\Users\{your username}
 The propmpt for user CLI is '>' where you click to enter your commands for Anaconda3.
 For exaple you can type this command to know wich conda have installed now:
    (base) C:\Users\{your username}>conda -V
 and the response for mine is 
                                    conda 4.5.12
 or if want to know the Anaconda3 version type:
    (base) C:\Users\{your username}>conda list anaconda
 and the response for mine is :
	                                #
									# Name                    Version                   Build  Channel
									anaconda                  custom                   py37_0
									anaconda-client           1.7.1                      py_0    conda-forge
									anaconda-navigator        1.9.6                    py37_0
									anaconda-project          0.8.2                      py_1    conda-forge
	
The docummentation for Anaconda3 can be find at
  https://docs.anaconda.com/

  
  That is all for now!
  Thanks."# w10-anaconda-3-install-on-i5" 
