Social Mapper patches to make it run stably on windows
# Installation on Windows

 - Install python 3.6 64 bit from the following link

		https://www.python.org/downloads/release/python-360/

 - export python binary in system path

		normally located at C:\Users\USERNAME\AppData\Local\Programs\Python\Python36
		also export C:\Users\USERNAME\AppData\Local\Programs\Python\Python36\Scripts

 - clone the code from this repository using

		git clone https://github.com/ZeeshanSultan/social-mapper
	(download zip via the download button or install git-scm incase of error)

 - Download and install cmake from this link

		https://cmake.org/files/v3.12/cmake-3.12.1-win64-x64.msi

 - open cmd and navigate to social mapper directory and enter these
   commands in sequence

		cd setup
		pip3 install dlib-19.8.1-cp36-cp36m-win_amd64.whl
		pip3 install -r requirements.txt
# Important Note
Some syntax of this code has been modified to make it compatible with Python3.6 if you face any errors do not hesitate to open any issue

# Instructions
For instructions about running the code see the original markdown file located at

- https://github.com/ZeeshanSultan/social-mapper/blob/master/README_old.md
