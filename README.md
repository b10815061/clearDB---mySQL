# clearDB---mySQL

## using cleardb as interface of mysql in heroku
what if the madarin shows to be ????

run (in mySQL) : show variables like '%char%';

and see the ```character_set_server``` row, if it's latin1 then there will be a problem

run (in mySQL) : set character_set_system = 'utf8';
