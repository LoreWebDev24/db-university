1) SELECT * FROM `students` JOIN degrees ON students.`degree_id` = degrees.`id` WHERE degrees.`name` = "Corso di Laurea in Economia";
1) SELECT students.`name`,students.`surname`, degrees.`name` FROM `students` JOIN degrees ON students.`degree_id` = degrees.`id` WHERE degrees.`name` = "Corso di Laurea in Economia";
2) SELECT * FROM degrees JOIN departments ON degrees.` department_id`  = departments.`id`  WHERE departments.`name` = "Dipartimento di Neuroscienze" AND degrees.`level`="magistrale"; 
3) SELECT count(`course_id`) as `numero_corsi` FROM `course_teacher` WHERE `course_teacher`.`teacher_id`= 44;
4) SELECT * FROM students JOIN `degrees` ON `students`.`degree_id` = `degrees`.`id` JOIN `departments` ON `degrees`.`department_id` = `departments`.`id` ORDER BY `students`.`surname` ASC;