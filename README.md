# MFC-Application-demo-using-Empty-Project-temple
  
  You can also create an MFC application from scratch.
  To create an MFC application, you need to follow the following Steps.
  
    1.  Open the Visual studio and click on the File → New → Project menu option.
    2.  You can now see the New Project dialog box.
    3.  select Empty project.
    4.  Enter project name ‘MFCDemoFromScratch’ in the Name field and click OK to continue. You will see that an empty project is created.
    5.  As it is an empty project now; we need to add a C++ file. So, right-click on the project and select Add → New Item…
    6.  Select C++ File (.cpp) in the middle pane and enter file name in the Name field and click Add button.
    7.  You can now see the main.cpp file added under the Source Files folder.
    8.  Let us add the following code in this file.

        #include <iostream> 
        using namespace std;  

        void main() { 
          cout << "***************************************\n"; 
          cout << "MFC Application form scratch using empty template"; 
          cout << "\n***************************************"; 
          getchar(); 
       }
