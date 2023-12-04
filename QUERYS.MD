1) SELECT * FROM `students` WHERE YEAR(`date_of_birth`) = '1990'; 
<!-- 1) 160 RESULTS V -->
2) SELECT * FROM `courses` WHERE `cfu` > 10;
<!-- 2) 1) 479 RESULTS V -->
3) SELECT * FROM `students` WHERE YEAR(`date_of_birth`) > '1990'
<!-- 3)  V Showing rows 0 - 24 (1814 total, Query took 0.0003 seconds.) -->
4) SELECT * FROM `courses` WHERE `period` LIKE 'I semestre' AND `year` LIKE '1';
<!-- 4) 286 RESULTS V -->