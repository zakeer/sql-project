# SQL Project

### Create Table Script

```
CREATE TABLE "student" (
	"id"	INTEGER ,
	"name"	TEXT NOT NULL,
	"class"	TEXT NOT NULL,
	"mark"	INTEGER NOT NULL DEFAULT 0,
	"gender"	TEXT NOT NULL,
	PRIMARY KEY("id" AUTOINCREMENT)
);
```

### INSERT SCRIPT
```
INSERT INTO student VALUES 
(1, 'syed', '10th', 43, 'male'),
(2, 'hussain', '8th', 44, 'male'),
(3, 'divya', '9th', 84, 'female'),
(4, 'koti', '8th', 99, 'male'),
(5, 'apsar', '6th', 44, 'male');
```

[Github Account](https://github.com/zakeer)
