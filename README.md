Struts2Hibernate-Sample
=======================
Jboss 7.0

CREATE TABLE CONTACTS
(   
    id      INT PRIMARY KEY AUTO_INCREMENT,
    firstname   VARCHAR(30),
    lastname    VARCHAR(30),
    cell_no     VARCHAR(15),
    email_id    VARCHAR(30),
    website     VARCHAR(150),
    birthdate   DATE,
    created     TIMESTAMP DEFAULT NOW()
);



http://localhost:8080/Struts2HibernateSample/index
