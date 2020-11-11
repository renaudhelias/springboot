# springboot
postgres springboot

```
CREATE TABLE public.poire
(
	id SERIAL PRIMARY KEY NOT NULL,
    saison character varying COLLATE pg_catalog."default"
)
WITH (
    OIDS = FALSE
)
TABLESPACE pg_default;
ALTER TABLE public.poire
    OWNER to postgres;
insert into poire(saison) values ('printemps');
insert into poire(saison) values ('été');
insert into poire(saison) values ('automne');
insert into poire(saison) values ('hiver');
```
