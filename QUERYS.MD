1) SELECT * FROM `students` WHERE YEAR(`date_of_birth`) = '1990'; 
<!-- 1) 160 RESULTS V -->
2) SELECT * FROM `courses` WHERE `cfu` > 10;
<!-- 2) 1) 479 RESULTS V -->
3) SELECT * FROM `students` WHERE TIMESTAMPDIFF(YEAR,CURRENT_DATE,date_of_birth);
<!-- 3)  V Showing rows 0 - 24 (5000 total, Query took 0.0003 seconds.) -->
4) SELECT * FROM `courses` WHERE `period` LIKE 'I semestre' AND `year` LIKE '1';
<!-- 4) 286 RESULTS V -->
5) SELECT * FROM `exams` WHERE date(`date`) = '2020-06-20' AND `hour` > '14:%';
<!-- 5) 21 RESULTS V  -->
6) SELECT * FROM `degrees` WHERE `level`= "magistrale";
<!-- 6) 38 RESULTS V  -->
7) SELECT COUNT(id) AS `departments_count` FROM `departments`; 
<!-- OPPURE IN QUESTO CASO SPECIFICO  -->
7) SELECT * FROM `departments`;
<!-- 7) 12 RESULTS V -->
8) SELECT COUNT(id) FROM `teachers` WHERE `phone` IS NULL;
<!-- 8) 50 RESULTS V --> 