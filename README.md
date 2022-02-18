# savefile
encoding UTF-8.

result original file. 
result2 DB all file.  

mongoimport --db SNdb --collection resultAll --type csv --headerline --file result2.csv

mongoimport --db SNdb --collection result_d --type csv --headerline --file result_d.csv

mongoimport --db SNdb --collection result_f --type csv --headerline --file result_f.csv

mongoimport --db SNdb --collection result_l --type csv --headerline --file result_l.csv


