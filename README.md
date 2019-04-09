# Python_training
Training for python programing as a beginer.

References for training.
1. "입문부터 실무까지 한 방에 끝내는 파이썬 프로그래밍", 혜지원, 조인석
2. "예제로 배우는 파이썬 프로그래밍", http://pythonstudy.xyz/
3. "Elegant Scipy", 
3. many sites....

for Mac
purpose : scipy

basic knowledge
1. $ is windows or MAC os prompt
2. (xxx)$ is virtual environment (ref : https://dojang.io/mod/page/view.php?id=2470)
3. pip
4. sudo
5. conda, atom,
6. scipy, numpy, jupyter,,, etc
7. linux kernel 
8. 

install python
 - ref : https://blog.naver.com/wskim012/221311600425

install miniconda, set virtual setting
 - ref : https://blog.naver.com/wskim012/221312816368
 
install ATOM
 - site : https://atom.io
 - ref : https://blog.naver.com/kim940225/221213597221
 - Setting Up Terminal Access for Atom
    Open Atom ( command-spacebar for spotlight, type Atom , and hit enter).
    Click the Atom menu in the top left corner.
    Click Install Shell Commands.
    Return to your terminal and enter which atom . ...
    Enter atom . to open your user directory in Atom.

Remeber,commands
for activation, $ conda activate myvenv # myvenv can replace other virtual environment.
for deactivation, $ conda decativate

(myvenv)$ ATOM
then, u can type on ATOM editor.

Done for Preparing.

Other virtual environment which is from "Elegant Scipy"
  - ref : https://github.com/AstinCHOI/elegant-scipy
  if already other virtual environment is activated, $ conda decativate
  if not, just start below.
  $ git clone https://github.com/AstinCHOI/elegant-scipy
  $ cd elegant-scipy

  $ conda env create --name elegant-scipy -f environment.yml
  $ source activate elegant-scipy
  if not work, close the terminal winodw and open it again. go to line 49.
  (elegant-scipy)$ jupyter notebook
 
