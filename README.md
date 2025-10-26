mkdir ~/mal_analyze
cp ~/Downloads/DragoMultiTOOL* ~/mal_analyze/
cd ~/mal_analyze

2.
file DragoMultiTOOL*

3.sha256sum DragoMultiTOOL*
4.tar -tvf DragoMultiTOOL*.tar.gz    
tar -xvf DragoMultiTOOL*.tar.gz    
4.sed -n '1,200p' file.py
less file.py

5.grep -nE "socket|subprocess|Popen|eval|exec|os.system|urllib|requests|base64|open\(" -R .
6.cat requirements.txt
