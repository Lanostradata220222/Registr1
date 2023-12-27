DROP DATABASE IF EXISTS Registr1db;
CREATE DATABASE IF NOT EXISTS Registr1db;
USE Registr1db;

DROP TABLE IF EXISTS Studenti;
CREATE TABLE IF NOT EXISTS Studenti(
    id
    firstname
    lastname
    classroom
);

DROP TABLE IF EXISTS Materia;
CREATE TABLE IF NOT EXISTS Materia (
    id
    name
    kind ENUM ('O', 'S', 'P') DEFAULT ''
);

