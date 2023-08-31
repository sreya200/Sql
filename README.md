# Sql
create database BooksDB;
create table books(
book_title varchar(20),
author varchar(20),
genre varchar(10),
publicationyear int,
price float(6,2)
);
insert into books values('harrypotter','J K Rolling','suspence',1997,888.00);
insert into books values('mr and mrs','james','adventure',2000,7888.00);
insert into books values('avathar','camaroal','advanture',2018,1888.00);
insert into books values('love','adih roy','romantic',2000,1222.00);
insert into books values('karnisangini','suhan','crime',2012,888.00);
insert into books values('100 days','ram','romantic',2015,700.00);
insert into books values('narniya','advert','adventure',1977,500.00);
insert into books values('my is gf is','kanyya','sci-fi',2020,1000.00);
insert into books values('zootopiya','ramshettie','comedy',2021,1200.00);
insert into books values('encantio','jane','suspence',2015,1000.00);
insert into books values('tangels','rollig','suspence',2014,1200.00);
select * from books;
select book_title from books;
update books set price=50 where book_title='harrypotter';
delete from books where book_title='love';
