I write this procedure for people which intend to use Anaconda3 on your personal computer/laptop
(which finally will create one Python environment for Machine [or Deep] Learning).

In my opinion, if intend to work with Anaconda3(which contain the 'conda.exe' as main tool) you can before 
uninstall any version of Python[s] which have installed in the past(is most important note!).
For that, you can use before to uninstall any version of local Python program using the following way to find 
the programs uninstall management from Winsows 10 Pro(W10 Pro):

    Control Panel -> Programs (the 'Uninstall  a program' option)

Manual procedure of installment for Anaconda3 consist in the folowing 3-steps:

1) check your hardware(HW) and software(SW) context(to know if apply this manual pocedure):
  go to taskbar on second icon(windows search) from your operation system(Windows 10 Pro) and type 'system'
  and choice to click the 'System Information" apllication and then check to view if have the following context:
  
  - Operation System(OS Name):   Microsoft(MS) Windows 10 Pro
  ...
  -System Type: x64 based PC
  ...
  -Processor:                    Intel(R)...(i5)
  ...
  -Installed Psical Memory(RAM): 8.00 GB (or more)
  ...
  
  Remark: In fact I have this experiment on my my laptop :
				...
				System Model: Inspiron 5567
				... 
          but I think work on many(or any) machines with Windowns 64-Bit
		  
2) go to any browser(I prefer Chrome but can use any browser) and write this address URL:
         https://www.anaconda.com/download/
   and click on(select) the   '64-Bit Graphical Installer(now it have and show 614.3 MB)'
   under 'Python 3.7 version *'(now refer to Python 3.7.1)
   Waiting and open your c:\Downloads system to see that you finish the download of file named:
         Anaconda3-2018.12-Windows-x86_64.exe
	
3) Finally,click on this file Anaconda3...-x86_64.exe crom c:Download directory to start the your installer.
   Accept all and then click 'Next' to 'Finish' the installment.
   Please Not modify anythink option!
   Normally the directory which contain entire Anaconda3 64 bits will be :
      C:\Users\{your username}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Anaconda3 (64-bit)

The Anaconda3 have two main components:
    Anaconda Navigator and
    Anaconda Prompt

Remarks:

Anaconda Navigator is one GUI=graphical user interface(or interaction) and Anaconda Prompt(my preference) is one client user interface=CLI.
The Anaconda Prompt in fact is one terminal window which show you one simple shell prompt like :
    (base) C:\Users\{your username}>
(base) is name for your current(default) environment and then follow the current path where is now located theyour user=prompt:
C:\Users\{your username}
 The propmpt for user CLI is '>' where you click to enter your commands for Anaconda3.
 For example you can type this command to know which 'conda' version have installed now:
 
    (base) C:\Users\{your username}> conda -V
    
 and the response for mine is 
                                     conda 4.5.12
				    
 or if want to know the Anaconda3 version(in fact which versions have all components from Anaconda3) then type:
 
    (base) C:\Users\{your username}> conda list anaconda
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
  Thanks.
  
  # w10-anaconda-3-install-on-i5 
