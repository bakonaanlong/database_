
CREATE DATABASE company_db;
USE company_db;

CREATE TABLE employees (
    id             INT AUTO_INCREMENT PRIMARY KEY,
    name           VARCHAR(100) NOT NULL,
    age            INT NOT NULL,
    gender         ENUM('M','F') NOT NULL,
    salary         DECIMAL(10,2) NOT NULL,
    department     VARCHAR(50) NOT NULL,
    position       VARCHAR(50) NOT NULL,
    year_of_entry  YEAR NOT NULL,
    hours_worked   INT NOT NULL
);

INSERT INTO employees (name, age, gender, salary, department, position, year_of_entry, hours_worked) VALUES
('James Carter',     34, 'M', 62000, 'Engineering', 'Software Engineer',   2018, 40),
('Maria Gonzalez',   29, 'F', 58000, 'Marketing',    'Marketing Specialist',2020, 38),
('Michael Chen',     34, 'M', 71000, 'Finance',      'Financial Analyst',  2016, 40),
('Sarah Johnson',    41, 'F', 85000, 'Engineering',  'Engineering Manager',2012, 45),
('David Kim',        29, 'M', 58000, 'Sales',        'Sales Executive',    2020, 42),
('Linda Brown',      37, 'F', 62000, 'HR',           'HR Manager',         2015, 40),
('Robert Davis',     45, 'M', 95000, 'Finance',      'Finance Director',   2010, 40),
('Emma Wilson',      26, 'F', 52000, 'Marketing',    'Marketing Specialist',2022, 38),
('James Whitfield',  41, 'M', 78000, 'Sales',        'Sales Manager',      2012, 44),
('Grace Lee',        34, 'F', 71000, 'Engineering',  'Software Engineer',  2016, 40),
('John Martinez',    29, 'M', 58000, 'Engineering',  'Software Engineer',  2020, 40),
('Maria Rodriguez',  37, 'F', 66000, 'Finance',      'Financial Analyst',  2015, 40),
('Michael Turner',   45, 'M', 62000, 'HR',           'HR Manager',         2010, 40),
('Sarah Ahmed',      26, 'F', 58000, 'Sales',        'Sales Executive',    2022, 42),
('David Wright',     34, 'M', 71000, 'Marketing',    'Marketing Manager',  2016, 40),
('Linda Chen',       41, 'F', 85000, 'Finance',      'Finance Director',   2012, 40),
('Robert Kim',       29, 'M', 52000, 'Engineering',  'Junior Developer',   2020, 40),
('Emma Davis',       37, 'F', 62000, 'Marketing',    'Marketing Specialist',2015, 38),
('James Nguyen',     26, 'M', 58000, 'Sales',        'Sales Executive',    2022, 42),
('Grace Patel',      45, 'F', 95000, 'Engineering',  'Engineering Manager',2010, 45),
('John Wilson',      34, 'M', 62000, 'HR',           'HR Generalist',      2018, 40),
('Maria Chen',       41, 'F', 78000, 'Sales',        'Sales Manager',      2012, 44),
('Michael Brown',    29, 'M', 58000, 'Marketing',    'Marketing Specialist',2020, 38),
('Sarah Kim',        37, 'F', 71000, 'Engineering',  'Software Engineer',  2016, 40),
('David Lee',        26, 'M', 52000, 'Engineering',  'Junior Developer',   2022, 40),
('Linda Martinez',   45, 'F', 62000, 'HR',           'HR Manager',         2010, 40),
('Robert Wilson',    34, 'M', 71000, 'Finance',      'Financial Analyst',  2018, 40),
('Emma Turner',      29, 'F', 58000, 'Sales',        'Sales Executive',    2020, 42),
('James Ahmed',      37, 'M', 66000, 'Finance',      'Financial Analyst',  2015, 40),
('Grace Wright',     41, 'F', 85000, 'Engineering',  'Engineering Manager',2012, 45);
