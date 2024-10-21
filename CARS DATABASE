# CARS-DATABASE
CREATE TABLE cars (
  brand VARCHAR(255),
  model VARCHAR(255),
  year INT
  );
SELECT * FROM cars;

INSERT INTO cars (brand,model,year)
VALUES
  ('Toyota','corolla','1975'),
  ('Audi','R8','2006'),
  ('jeep','avenger','2008');
SELECT * FROM cars;
SELECT brand, year FROM cars;

ALTER TABLE cars
ADD color VARCHAR(255);
SELECT * FROM cars;

UPDATE cars
SET color = 'white'
WHERE brand = 'Toyota';
SELECT * FROM cars;

UPDATE cars
SET color = 'red'
WHERE brand = 'Audi';
SELECT * FROM cars;

UPDATE cars
SET color = 'pink'
WHERE brand = 'jeep';
SELECT * FROM cars;

ALTER TABLE cars
DROP COLUMN color;
SELECT * FROM cars;

DELETE FROM cars
WHERE brand ='Toyota';
SELECT * FROM cars;
