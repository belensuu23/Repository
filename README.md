# Repository

(c) 2017 Microsoft Corporation. Todos los derechos reservados.

C:\Users\Ana Barrionuevo>CD C:\python

C:\python>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 7E9C-BA08

 Directorio de C:\python

05/05/2018  12:03    <DIR>          .
05/05/2018  12:03    <DIR>          ..
05/05/2018  12:03    <DIR>          DLLs
05/05/2018  12:02    <DIR>          Doc
05/05/2018  12:02    <DIR>          include
05/05/2018  12:03    <DIR>          Lib
05/05/2018  12:03    <DIR>          libs
28/03/2018  16:14            30.340 LICENSE.txt
28/03/2018  16:14           392.371 NEWS.txt
28/03/2018  16:11            97.944 python.exe
28/03/2018  16:08            58.520 python3.dll
28/03/2018  16:08         3.303.064 python36.dll
28/03/2018  16:11            96.408 pythonw.exe
13/05/2018  16:43    <DIR>          Scripts
05/05/2018  12:03    <DIR>          tcl
05/05/2018  12:03    <DIR>          Tools
09/06/2016  22:46            83.784 vcruntime140.dll
               7 archivos      4.062.431 bytes
              10 dirs  870.991.409.152 bytes libres

C:\python>CD C:\python\Scripts

C:\python\Scripts>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 7E9C-BA08

 Directorio de C:\python\Scripts

13/05/2018  16:43    <DIR>          .
13/05/2018  16:43    <DIR>          ..
05/05/2018  12:03            89.447 easy_install-3.6.exe
05/05/2018  12:03            89.447 easy_install.exe
13/05/2018  16:43    <DIR>          my_proyecto
05/05/2018  12:04            89.419 pip.exe
05/05/2018  12:04            89.419 pip3.6.exe
05/05/2018  12:04            89.419 pip3.exe
05/05/2018  12:09            89.426 virtualenv.exe
               6 archivos        536.577 bytes
               3 dirs  870.973.874.176 bytes libres

C:\python\Scripts>pip3.6.exe install virtualenv
Requirement already satisfied: virtualenv in c:\python\lib\site-packages
You are using pip version 9.0.3, however version 10.0.1 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.

C:\python\Scripts>
C:\python\Scripts>python -m pip install --upgrade
"python" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\python\Scripts>
C:\python\Scripts>python -m pip install --upgrade pip
"python" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\python\Scripts>python -m pip install --upgrade pip
"python" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\python\Scripts>
C:\python\Scripts>CD C:\python

C:\python>python -m pip install --upgrade pip
Collecting pip
  Downloading https://files.pythonhosted.org/packages/0f/74/ecd13431bcc456ed390b44c8a6e917c1820365cbebcb6a8974d1cd045ab4/pip-10.0.1-py2.py3-none-any.whl (1.3MB)
    100% |████████████████████████████████| 1.3MB 60kB/s
Installing collected packages: pip
  Found existing installation: pip 9.0.3
    Uninstalling pip-9.0.3:
      Successfully uninstalled pip-9.0.3
Successfully installed pip-10.0.1

C:\python>cd scripts

C:\python\Scripts>virtualenv --version
15.2.0

C:\python\Scripts>mkdir my_project

C:\python\Scripts>cd my_project

C:\python\Scripts\my_project>cd..

C:\python\Scripts>virtualenv myvirtualenv
Using base prefix 'c:\\python'
New python executable in C:\python\Scripts\myvirtualenv\Scripts\python.exe
Installing setuptools, pip, wheel...done.

C:\python\Scripts>cd
C:\python\Scripts

C:\python\Scripts>dir..
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 7E9C-BA08

 Directorio de C:\python

05/05/2018  12:03    <DIR>          .
05/05/2018  12:03    <DIR>          ..
05/05/2018  12:03    <DIR>          DLLs
05/05/2018  12:02    <DIR>          Doc
05/05/2018  12:02    <DIR>          include
05/05/2018  12:03    <DIR>          Lib
05/05/2018  12:03    <DIR>          libs
28/03/2018  16:14            30.340 LICENSE.txt
28/03/2018  16:14           392.371 NEWS.txt
28/03/2018  16:11            97.944 python.exe
28/03/2018  16:08            58.520 python3.dll
28/03/2018  16:08         3.303.064 python36.dll
28/03/2018  16:11            96.408 pythonw.exe
13/05/2018  21:28    <DIR>          Scripts
05/05/2018  12:03    <DIR>          tcl
05/05/2018  12:03    <DIR>          Tools
09/06/2016  22:46            83.784 vcruntime140.dll
               7 archivos      4.062.431 bytes
              10 dirs  870.946.025.472 bytes libres

C:\python\Scripts>dir..
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 7E9C-BA08

 Directorio de C:\python

05/05/2018  12:03    <DIR>          .
05/05/2018  12:03    <DIR>          ..
05/05/2018  12:03    <DIR>          DLLs
05/05/2018  12:02    <DIR>          Doc
05/05/2018  12:02    <DIR>          include
05/05/2018  12:03    <DIR>          Lib
05/05/2018  12:03    <DIR>          libs
28/03/2018  16:14            30.340 LICENSE.txt
28/03/2018  16:14           392.371 NEWS.txt
28/03/2018  16:11            97.944 python.exe
28/03/2018  16:08            58.520 python3.dll
28/03/2018  16:08         3.303.064 python36.dll
28/03/2018  16:11            96.408 pythonw.exe
13/05/2018  21:28    <DIR>          Scripts
05/05/2018  12:03    <DIR>          tcl
05/05/2018  12:03    <DIR>          Tools
09/06/2016  22:46            83.784 vcruntime140.dll
               7 archivos      4.062.431 bytes
              10 dirs  870.941.327.360 bytes libres

C:\python\Scripts>source myvirtualenv/bin/activate
"source" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\python\Scripts>source myvirtualenv\bin\activate
"source" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\python\Scripts>source myvirtualenv\bin\activate.bat
"source" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\python\Scripts>virtualenv myvirtualenv
Using base prefix 'c:\\python'
New python executable in C:\python\Scripts\myvirtualenv\Scripts\python.exe
Installing setuptools, pip, wheel...done.

C:\python\Scripts>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 7E9C-BA08

 Directorio de C:\python\Scripts

13/05/2018  21:28    <DIR>          .
13/05/2018  21:28    <DIR>          ..
05/05/2018  12:03            89.447 easy_install-3.6.exe
05/05/2018  12:03            89.447 easy_install.exe
13/05/2018  21:28    <DIR>          myvirtualenv
13/05/2018  21:25    <DIR>          my_project
13/05/2018  21:19            93.013 pip.exe
13/05/2018  21:19            93.013 pip3.6.exe
13/05/2018  21:19            93.013 pip3.exe
05/05/2018  12:09            89.426 virtualenv.exe
               6 archivos        547.359 bytes
               4 dirs  871.024.009.216 bytes libres

C:\python\Scripts>activate.bat
"activate.bat" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\python\Scripts>CD C:\phyton\scripts\myvirtualenv\scripts
El sistema no puede encontrar la ruta especificada.

C:\python\Scripts>CD
C:\python\Scripts

C:\python\Scripts>CD C:\python\Scripts\myvirtualenv\Scripts

C:\python\Scripts\myvirtualenv\Scripts>activate.bat

(myvirtualenv) C:\python\Scripts\myvirtualenv\Scripts>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 7E9C-BA08

 Directorio de C:\python\Scripts\myvirtualenv\Scripts

13/05/2018  21:28    <DIR>          .
13/05/2018  21:28    <DIR>          ..
13/05/2018  21:28             2.195 activate
13/05/2018  21:28               774 activate.bat
13/05/2018  21:28             8.325 activate.ps1
13/05/2018  21:28             1.137 activate_this.py
13/05/2018  21:28               508 deactivate.bat
13/05/2018  21:41            89.476 easy_install-3.6.exe
13/05/2018  21:41            89.476 easy_install.exe
13/05/2018  21:41            89.458 pip.exe
13/05/2018  21:41            89.458 pip3.6.exe
13/05/2018  21:41            89.458 pip3.exe
13/05/2018  21:41            97.944 python.exe
13/05/2018  21:41            58.520 python3.dll
13/05/2018  21:41         3.303.064 python36.dll
13/05/2018  21:41            96.408 pythonw.exe
13/05/2018  21:41            89.455 wheel.exe
              15 archivos      4.105.656 bytes
               2 dirs  871.184.982.016 bytes libres

(myvirtualenv) C:\python\Scripts\myvirtualenv\Scripts>deactivate.bat
C:\python\Scripts\myvirtualenv\Scripts>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 7E9C-BA08

 Directorio de C:\python\Scripts\myvirtualenv\Scripts

13/05/2018  21:28    <DIR>          .
13/05/2018  21:28    <DIR>          ..
13/05/2018  21:28             2.195 activate
13/05/2018  21:28               774 activate.bat
13/05/2018  21:28             8.325 activate.ps1
13/05/2018  21:28             1.137 activate_this.py
13/05/2018  21:28               508 deactivate.bat
13/05/2018  21:41            89.476 easy_install-3.6.exe
13/05/2018  21:41            89.476 easy_install.exe
13/05/2018  21:41            89.458 pip.exe
13/05/2018  21:41            89.458 pip3.6.exe
13/05/2018  21:41            89.458 pip3.exe
13/05/2018  21:41            97.944 python.exe
13/05/2018  21:41            58.520 python3.dll
13/05/2018  21:41         3.303.064 python36.dll
13/05/2018  21:41            96.408 pythonw.exe
13/05/2018  21:41            89.455 wheel.exe
              15 archivos      4.105.656 bytes
               2 dirs  871.289.544.704 bytes libres

C:\python\Scripts\myvirtualenv\Scripts>activate.bat

(myvirtualenv) C:\python\Scripts\myvirtualenv\Scripts>pip install nose
Collecting nose
  Downloading https://files.pythonhosted.org/packages/15/d8/dd071918c040f50fa1cf80da16423af51ff8ce4a0f2399b7bf8de45ac3d9/nose-1.3.7-py3-none-any.whl (154kB)
    100% |████████████████████████████████| 163kB 143kB/s
Installing collected packages: nose
Successfully installed nose-1.3.7

(myvirtualenv) C:\python\Scripts\myvirtualenv\Scripts>pip install rednose
Collecting rednose
  Downloading https://files.pythonhosted.org/packages/3a/a8/4b73ae7466c2e9b63b3c4d66040d1c0eda1f764812353753702546d8c87f/rednose-1.3.0.tar.gz
Requirement already satisfied: setuptools in c:\python\scripts\myvirtualenv\lib\site-packages (from rednose) (39.1.0)
Collecting termstyle>=0.1.7 (from rednose)
  Downloading https://files.pythonhosted.org/packages/65/53/4dfdfe12b499f375cc78caca9cf146c01e752bab7713de4510d35e3da306/termstyle-0.1.11.tar.gz
Collecting colorama (from rednose)
  Downloading https://files.pythonhosted.org/packages/db/c8/7dcf9dbcb22429512708fe3a547f8b6101c0d02137acbd892505aee57adf/colorama-0.3.9-py2.py3-none-any.whl
Building wheels for collected packages: rednose, termstyle
  Running setup.py bdist_wheel for rednose ... done
  Stored in directory: C:\Users\Ana Barrionuevo\AppData\Local\pip\Cache\wheels\21\be\74\e74fbccdaf7ab983f847153b2708e4d1722801ce7265dfa643
  Running setup.py bdist_wheel for termstyle ... done
  Stored in directory: C:\Users\Ana Barrionuevo\AppData\Local\pip\Cache\wheels\93\0c\cf\1d134a42237c338ee1d733c81b92d95f6d04d9531bf4c2a9a1
Successfully built rednose termstyle
Installing collected packages: termstyle, colorama, rednose
Successfully installed colorama-0.3.9 rednose-1.3.0 termstyle-0.1.11

(myvirtualenv) C:\python\Scripts\myvirtualenv\Scripts>mkdir _test_

(myvirtualenv) C:\python\Scripts\myvirtualenv\Scripts>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 7E9C-BA08

 Directorio de C:\python\Scripts\myvirtualenv\Scripts

13/05/2018  22:04    <DIR>          .
13/05/2018  22:04    <DIR>          ..
13/05/2018  21:28             2.195 activate
13/05/2018  21:28               774 activate.bat
13/05/2018  21:28             8.325 activate.ps1
13/05/2018  21:28             1.137 activate_this.py
13/05/2018  21:28               508 deactivate.bat
13/05/2018  21:41            89.476 easy_install-3.6.exe
13/05/2018  21:41            89.476 easy_install.exe
13/05/2018  22:03            93.041 nosetests-3.4.exe
13/05/2018  22:03            93.041 nosetests.exe
13/05/2018  21:41            89.458 pip.exe
13/05/2018  21:41            89.458 pip3.6.exe
13/05/2018  21:41            89.458 pip3.exe
13/05/2018  21:41            97.944 python.exe
13/05/2018  21:41            58.520 python3.dll
13/05/2018  21:41         3.303.064 python36.dll
13/05/2018  21:41            96.408 pythonw.exe
13/05/2018  21:41            89.455 wheel.exe
13/05/2018  22:04    <DIR>          _test_
              17 archivos      4.291.738 bytes
               3 dirs  871.345.324.032 bytes libres

(myvirtualenv) C:\python\Scripts\myvirtualenv\Scripts>pip install faker
Collecting faker
  Downloading https://files.pythonhosted.org/packages/67/bf/103159d314fd1c42996ce2e978be5261df3983b8078a525c044bd2d2dd61/Faker-0.8.14-py2.py3-none-any.whl (741kB)
    100% |████████████████████████████████| 747kB 129kB/s
Collecting text-unidecode==1.2 (from faker)
  Downloading https://files.pythonhosted.org/packages/79/42/d717cc2b4520fb09e45b344b1b0b4e81aa672001dd128c180fabc655c341/text_unidecode-1.2-py2.py3-none-any.whl (77kB)
    100% |████████████████████████████████| 81kB 117kB/s
Collecting six>=1.10 (from faker)
  Downloading https://files.pythonhosted.org/packages/67/4b/141a581104b1f6397bfa78ac9d43d8ad29a7ca43ea90a2d863fe3056e86a/six-1.11.0-py2.py3-none-any.whl
Collecting python-dateutil>=2.4 (from faker)
  Downloading https://files.pythonhosted.org/packages/cf/f5/af2b09c957ace60dcfac112b669c45c8c97e32f94aa8b56da4c6d1682825/python_dateutil-2.7.3-py2.py3-none-any.whl (211kB)
    100% |████████████████████████████████| 215kB 144kB/s
Installing collected packages: text-unidecode, six, python-dateutil, faker
Successfully installed faker-0.8.14 python-dateutil-2.7.3 six-1.11.0 text-unidecode-1.2

(myvirtualenv) C:\python\Scripts\myvirtualenv\Scripts>nosetests --rednose _test_ -v-d
Usage: nosetests [options]

nosetests: error: no such option: --

(myvirtualenv) C:\python\Scripts\myvirtualenv\Scripts> CD C:\python\Scripts\myvirtualenv

(myvirtualenv) C:\python\Scripts\myvirtualenv>nosetests --rednose _test_ -v -d

-----------------------------------------------------------------------------
0 tests run in 0.000 seconds (0 tests passed)

(myvirtualenv) C:\python\Scripts\myvirtualenv>
