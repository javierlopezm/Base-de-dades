# Base-de-dades

Url repositorio: https://github.com/javierlopezm/Base-de-dades.git

No entendí concretamente qué es lo que nos piden en el Sprint 1 Ejercicio 1 "explica les diferents taules i variables que hi ha", lo pregunté en el foro (https://itacademy.barcelonactiva.cat/mod/forum/discuss.php?d=398) el 15 de setembre 2022, pero no obtuve respuesta. No obstante, expongo lo que yo he entendio que nos piden.

- tb_genre
Su pk es genre_id

- tb_movie 
Su pk es movie_id
Contiene una fk movie_genre_id que referencia a tb_genre

- tb_role
Su pk es role_id

- tb_person
Su pk es person_id
Su fk es person_parent_id que hace referencia a sí misma

- tb_movie_person
Su pk está compuesta por 3 atributos: movie_id, person_id y role_id
La fk movie_id ref. tb_movie
La fk person_id ref. tb_person
La fk role_id ref. tb_role
