Steps to Run the Application 


1. install xaamp
2. install python
3. pip install yaml
4. pip install flask



Create tables : 

CREATE TABLE `employee` (
  `employee_id` int(10) NOT NULL,
  `first_name` varchar(255) NOT NULL,
  `last_name` varchar(255) NOT NULL,
  `email_id` varchar(255) NOT NULL,
  `department_name` varchar(255) NOT NULL,
  `date_of_birth` date NOT NULL DEFAULT current_timestamp(),
  `department_id` int(10) NOT NULL,
  `hire_date` date DEFAULT NULL,
  `job_id` int(11) NOT NULL
)




CREATE TABLE `jobs` (
  `job_id` int(10) NOT NULL,
  `job_title` varchar(255) NOT NULL,
  `max_salary` varchar(255) NOT NULL,
  `min_salary` varchar(255) NOT NULL
) 



CREATE TABLE `login_data` (
  `login_user` varchar(255) NOT NULL,
  `login_password` varchar(255) NOT NULL,
  `login_type` varchar(10) NOT NULL
) 




CREATE TABLE `department` (
  `department_id` int(10) NOT NULL,
  `department_name` varchar(255) NOT NULL,
  `manager_id` int(10) NOT NULL,
  `manager_name` varchar(255) NOT NULL
) 


Run the app
