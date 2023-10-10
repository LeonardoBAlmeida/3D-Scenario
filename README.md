# 3D-Scenery

An 3D scenery for Computer Graphics discipline made in C++ using OpenGl glut.h library

# Install Configs for glut.h

This is a tutorial for installing cg library freeglut (gl/glut.h) in windows .
there are many other ways too install it , but i found using vcpkg is much easier. 
commands:-
*to clone using git bash:-
git clone https://github.com/Microsoft/vcpkg.git

*open powershell and then give commands:-
1.  cd path_of_folder_you_cloned
2. .\vcpkg\bootstrap-vcpkg.bat
3. cd .\vcpkg
4. .\vcpkg integrate install
5.  .\vcpkg install freeglut:x64-windows

Once the installation is done you can start using/developing your CG project using openGl. the libraries should be included.