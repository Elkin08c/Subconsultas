- Esta consulta  se mostrará la fecha de inicio, la fecha de finalización de la conferencia realizada
  
```
SELECT start_date, end_date
FROM event
ORDER BY start_date;
```
<img src="./Subconsultas 1.png" alt="drawing" width="500"/>


- En la siguiente  consulta se nos devolverá una lista con el código de registro, la fecha de registro y si el miembro asistió o no, ordenada por fecha de registro.
  
```
SELECT code, registered_at, assisted
FROM register
ORDER BY registered_at;
```
<img src="./Subconsultas 2.png" alt="drawing" width="500"/>
