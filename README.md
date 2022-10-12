This is my first sentence in Data Analytics Foundations Class.
/*

-- I'm creating a new data-table in the next query!

CREATE TABLE public.products
	//CREATE TABLE	--> this is the command to create a SQL table
	//public 		--> public is where I am placeing the table
	//products 		--> is the name of the table
(
    product_id integer NOT NULL,
    //product_id	--> this is a feature/column on my table named 'product_id'
    //integer		--> this declares the colum to accept integers
    //NOT NULL		--> this field or column cannot be empty

    title character varying(255) COLLATE pg_catalog."default",
    //title			--> this is a feature/column on my table named 'title'
    // character varying(255)	--> this declares the colum to accept character 0-255

    price numeric,
    //price			--> this is a feature/column on my table named 'price'
    //numeric		--> this declares the colum to accept numeric

    created_at timestamp with time zone,
    //created_at	--> this is a feature/column on my table named 'created_at'
    //timestamp		--> this declares the colum to accept time-date formats

    deleted_at timestamp with time zone,
    //deleted_at	--> this is a feature/column on my table named 'deleted_at'
    //timestamp		--> this declares the colum to accept time-date formats

    tags character varying(255) COLLATE pg_catalog."default",
    //tags			--> this is a feature/column on my table named 'tags'
    // character varying(255)	--> this declares the colum to accept character 0-255

    CONSTRAINT products_pkey PRIMARY KEY (product_id)
    //product_id	--> this is a feature/column on my table named 'product_id'
    //CONSTRAINT products_pkey PRIMARY KEY		
    				--> this declares the colum to be the primary key f
);
*/

In slack copied for Message foundations-fall22


INSERT INTO PRODUCTS VALUES (1, 'Dictionary',9.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Book}');
INSERT INTO PRODUCTS VALUES (2, 'Python Book',29.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','"{Book,Programming,Python}"');
INSERT INTO PRODUCTS VALUES (3, 'Ruby Book',27.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','"{Book,Programming,Ruby}"');
INSERT INTO PRODUCTS VALUES (4, 'Baby Book',7.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','"{Book,Children,Baby}"');
INSERT INTO PRODUCTS VALUES (5, 'Coloring Book',5.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','"{Book,Children}"');
INSERT INTO PRODUCTS VALUES (6, 'Desktop Computer',499.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Technology}');
INSERT INTO PRODUCTS VALUES (7, 'Laptop Computer',899.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Technology}');
INSERT INTO PRODUCTS VALUES (8, 'MP3 Player',108.00,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','"{Technology,Music}"');
INSERT INTO PRODUCTS VALUES (9, '"42"" LCD TV"',499.00,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','"{Technology,TV}"');
INSERT INTO PRODUCTS VALUES (10, '"42"" Plasma TV"',529.00,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','"{Technology,TV}"');
INSERT INTO PRODUCTS VALUES (11, 'Classical playlist',9.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Music}');
INSERT INTO PRODUCTS VALUES (12, 'Holiday playlist',9.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Music}');
INSERT INTO PRODUCTS VALUES (13, 'Country playlist',9.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Music}');
INSERT INTO PRODUCTS VALUES (14, 'Pop playlist',9.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Music}');
INSERT INTO PRODUCTS VALUES (15, 'Electronic playlist',9.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Music}');
INSERT INTO PRODUCTS VALUES (16, 'Comedy Movie',14.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','"{Movie,Comedy}"');
INSERT INTO PRODUCTS VALUES (17, 'Documentary',14.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Movie}');
INSERT INTO PRODUCTS VALUES (18, 'Romantic',14.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Movie}');
INSERT INTO PRODUCTS VALUES (19, 'Drama',14.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Movie}');
INSERT INTO PRODUCTS VALUES (20, 'Action',14.99,'Jan  1 2011  2:00PM','Jan  1 1900 12:00AM','{Movie}');
INSERT INTO PRODUCTS VALUES (21, 'Etch-A-Sketch',6.99,'May 12 2020  4:04PM','Jan  1 1900 12:00AM','{Children}');
INSERT INTO PRODUCTS VALUES (22, 'Hula Hoop',10.99,'May 14 2020  5:15PM','Jan  1 1900 12:00AM','{Children}');
INSERT INTO PRODUCTS VALUES (23, 'Mario Kart',299.00,'May 14 2020  5:29PM','Jan  1 1900 12:00AM','"{Children,Technology}"');
INSERT INTO PRODUCTS VALUES (25, 'ipod nano',79.00,'Oct 28 2020  1:18PM','Jan  1 1900 12:00AM','"{Technology,Music}"');
INSERT INTO PRODUCTS VALUES (26, 'An ice cold beer',19.99,'Oct 28 2020  1:46PM','Jan  1 1900 12:00AM','');
INSERT INTO PRODUCTS VALUES (27, 'Adult Coloring Book',9.99,'Oct 28 2020  1:20PM','Jan  1 1900 12:00AM','');
INSERT INTO PRODUCTS VALUES (29, 'New Book',12.00,'Oct 28 2020  1:33PM','Jan  1 1900 12:00AM','{Book}');
INSERT INTO PRODUCTS VALUES (52, 'Boogie Board',60.00,'May 14 2020  5:58PM','Jan  1 1900 12:00AM','{Children}');
INSERT INTO PRODUCTS VALUES (87, 'Adult coloring book',9.99,'Oct 28 2020  1:21PM','Jan  1 1900 12:00AM','');
INSERT INTO PRODUCTS VALUES (123, 'A fresh hot pizza',19.99,'Oct 28 2020  1:44PM','Jan  1 1900 12:00AM','');

Select * from products;
press control enter
