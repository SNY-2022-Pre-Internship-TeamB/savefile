# savefile
encoding UTF-8.

우분투와 도커가 한글파일을 읽을 수 있도록 먼저 셋팅을 하셔야합니다.

result original file. 
result2 DB all file.  

mongoimport --db SNdb --collection resultAll --type csv --headerline --file result2.csv

cd typeClass

mongoimport --db SNdb --collection result_d --type csv --headerline --file result_d.csv

mongoimport --db SNdb --collection result_f --type csv --headerline --file result_f.csv

mongoimport --db SNdb --collection result_l --type csv --headerline --file result_l.csv


