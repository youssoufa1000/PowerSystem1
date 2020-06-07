                    POWER SYSTEM TOOLBOX
           PROGRAMS AND M FILES FOR CHAPTER EXAMPLES

The diskette included with the book contains all the developed
functions and chapter examples. The M-files reside in the
directories labeled Folder 1 and Folder 2. The file names for
chapter examples begin with the letters chp. For example, the
M-file for Example 11.4 is chp11ex4.  The appendix examples begin
with exa and exb and a number. The disk contains a file called
setup.exe that automates installation of all the files. Insert the
diskette in the disk drive and use Windows to view its contents.
For automatic installation double click on the setup.exe icon to
start the installation. The installation program will prompt you
for the location of the MATLAB directory and the name of the
directory where you would like the files to be installed.
Alternatively, you can copy the M-files manually. To do this,
create a subdirectory, such as power, where the MATLAB toolbox
resides. Copy  all the files from Folder 1 and Folder 2 to the
subdirectory matlab\toolbox\power.

You must update the MATLAB search path to include "power" directory.
In the MATLAB 5 Command Window open the Path Browser by selecting
Set Path from the File menu.  From the Path menu choose Add to
Path. Select the directory to add, choose Add to back option and
press OK to add to the current MATLAB directory area. Save before
exiting the Path Browser.

If you are running MATLAB 4 edit the matlabrc.m located in the
subdirectory matlab\bin, where the search paths are specified.
Describe the subdirectory just created by adding the statement

';\matlab\toolbox\power', ... at the end of this file.

The Power System Toolbox requires MATLAB software by MathWorks,
Inc. The MATLAB must be purchased under a license agreement from
the MathWorks, Inc. The Power System Toolbox may also be used with
the Student Edition of MATLAB. Some Examples need the Student
Edition or Professional Version of SIMULINK.

MATLAB® and SIMULINK® are registered trademarks of The MathWorks, Inc.


If you encounter any bugs or problems please contact me at the
following e-mail addresses or visit my Web sites for updates and
information on this product.

Web site:   http://www.msoe.edu/~saadat
            http://www.home.att.net/~saadat
e-mail:     saadat@msoe.edu
            saadat@worldnet.att.net

Hadi Saadat
Milwaukee School of Engineering
Spring 1998
