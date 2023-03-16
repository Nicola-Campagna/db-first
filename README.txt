DATABASE CONCESSIONARIA AUTO USATE

Cars

Column                      Type              Attributes                                  Index

id                          int               autoincrement(not null , unique)            primary key
modello                     varchar(30)       not null                                    index
costruttore                 varchar(30)       not null                                    index
targa                       varchar(16)       not null default('veicolo non targato')     
numero_telaio               char(18)          not null
km                          mediumint         null                                        index
anno_immatricolazione       year              null                                        index
anno_costruzione            year              null
colore                      varchar(40)       null
codice_colore               varchar(15)       null
alimentazione               varchar(12)       not null                                    index
cavalli                     int               not null                                    index
portata                     tinyint           not null                                    index
porte                       tinyint           not null                                    index
cilindrata                  tinyint           not null                                    index
emissioni                   varchar(10)       not null                                    index