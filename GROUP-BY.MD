1) SELECT COUNT(`id`) 'studenti_iscritti', YEAR(`enrolment_date`) AS 'anno' FROM students GROUP BY YEAR(`enrolment_date`);
2) SELECT COUNT(*) `count_teachers`, `office_address` FROM teachers GROUP BY `office_address`;
3) SELECT COUNT(`exam_id`), AVG(`vote`) AS `media` FROM `exam_student` GROUP BY `exam_id`;
4) SELECT COUNT(`id`) AS `courses`,`department_id` FROM degrees GROUP BY `department_id`;