# PascGaloisJE

The PascGalois JE and PascGalois Zn programs were developed in support of the *The PascGalois Project: Visualizing Abstract Mathematics*, created by Dr. Mike Bardzell and Dr. Kathleen Shannon at Salisbury University in Salisbury Maryland.  The PascGalois Project was made possible through two grants from the National Science Foundation, DUE-0087644 and DUE-0339477.  For more information, articles, and classroom resources, please see our website at **[The PascGalois Project: Visualizing Abstract Mathematics](https://faculty.salisbury.edu/~despickler/pascgalois/index.html)**.

---

**Download the Current Version (2.6.1)**

**Prerequisite:** If the Java JRE is not installed on your computer download and install the current version of the Java JRE (Version 8 or later).

**Windows Users**

The Windows distribution of this program is either as a single stand-alone executable file, PascGalois.exe, or as a Windows installer, PascGaloisJE_Setup.exe.

- For the stand-alone executable file:
  - Download the **[PascGalois.exe](https://github.com/mathprofdes/PascGaloisJE/releases/download/v2.6.1/PascGalois.exe)** file. 
  - From Windows Explorer double-click the PascGalois.exe file.
- For the Windows installer:
  - Download the **[PascGaloisJE_Setup.exe](https://github.com/mathprofdes/PascGaloisJE/releases/download/v2.6.1/PascGaloisJE_Setup.exe)** file. 
  - From Windows Explorer double-click the PascGaloisJE_Setup.exe file and follow the instructions on the screen. This will place links to the PascGalois JE program in your Start menu.

**Linux and MacOS Users**

The software is being distributed as an executable jar file. 
- Download the **[PascGalois.jar](https://github.com/mathprofdes/PascGaloisJE/releases/download/v2.6.1/PascGalois.jar)** file. 
- In most cases you can simply double-click it from your system's file browser. You can also run it from the command-line with
`java -jar PascGalois.jar`

**Other Files**

- The **[ProgramIcon.png](https://github.com/mathprofdes/PascGaloisJE/releases/download/v2.6.1/ProgramIcon.png)** file is just a png image file of the application icon, for shortcuts if you wish to use one.
- The **[PascGaloisJE_Users_Manual.pdf](https://github.com/mathprofdes/PascGaloisJE/releases/download/v2.6.1/PascGaloisJE_Users_Manual.pdf)** file is a short document to help you get started with the program and its functionality.  Note that this was written prior to the current version but contains descriptions of all the program features.  One exception to this is that the current version removed the 3-D viewer for 2-D automata. This removed the dependency on third party libraries and made the program more stable across platforms.

--- 

**Program Description**

PascGalois JE is a platform independent program developed for the exploration of one and two dimensional cellular automata over finite group structures. The supported group structures are Zn, Zn (under multiplication), Dn, Sn, the Quaternions, Qn (Generalized Quaternions) and Cn (Dicyclic groups). This is a Java application, so if the Java JRE is not installed on your computer download and install the current version of the Java JRE (Version 8 or later). You can get the most current version at the Java Web Site.  The software was created using the older Java Swing API, so the appearance is a little retro. This software has been tested on Windows 10 and 11, Linux Mint 21, and MacOS Mojave.

**Program Features**

- Supported Group Structures: Zn, Zn (under multiplication), Dn, Sn, the Quaternions, Qn (Generalized Quaternions) and Cn (Dicyclic groups).
- The user can also input their own structure by specifying an operation table.
- There is an advanced input option that allows the user to use arbitrary Cartesian products and quotient groups of any of the above structures.
- Supports one and two dimensional finite and infinite automata.
- Group calculator with subgroup and coset generators.
- User defined update rules that can use up to 20 previous timesteps and a support radius of 100.
- User defined seeds that can use up to 20 previous timesteps and a support radius of 100.
- Complete color and image manipulation facilities.
- Advanced counting facilities for fractal dimension calculations, cycles and automata death.
- POV-Ray export facilities for 2-D automata.
- Level and probability density plot capabilities.

**Note:** If you only need to explore cellular automata over Zn but want the added ability to use both addition and multiplication in the update rule, you might be interested in the PascGalois Zn program that is available in my PascGaloisZn repository.

---

**Screenshots**

![Screenshot of program.](/Version_2_6_1/Screenshots/PascGaloisPic001t.png)
![Screenshot of program.](/Version_2_6_1/Screenshots/PascGaloisPic002t.png)
![Screenshot of program.](/Version_2_6_1/Screenshots/PascGaloisPic003t.png)
![Screenshot of program.](/Version_2_6_1/Screenshots/PascGaloisPic004t.png)

