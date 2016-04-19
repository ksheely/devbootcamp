+# devbootcamp
+_Recordly_: Recordly will be an application that allows for users to input and store their record collection. When complete, the user should be able to view their record collection, view a list of their "favorite" albums and/or songs, etc. Duplicate albums/songs should not be allowed. They should be able to "favorite" any of album/song/artist.

Step 1: Design User interface 
+   By designing in Photoshop (or another interface desinger) how the page will look like before coding starts, it saves a lot of time later in desiding how everything will, if it will fit, back-end requirements, and table layouts in the database.

Step 2: Code User Interface
+   Take design from Step 1 to create basic HTML layout of fields, forms, nav bar, etc. Helps in making sure that design will work, and font-end code is the same on each page.

Step 3: Design Database tables
+   Helps when going to server-side code to have a table ready to go (and even some test cases alread inserted)

Step 4: Server-side code
   (Many sub-steps as this part will be busier)
+   3.1: Inserts: Handle inserting new albums and records (in insert.php)
+   3.2: Update: Handle what a favorite will look like and handles (using AJAX allows smoother page handling for user)
+   3.3: Validation: Validate duplications in album inserts
     
Step 5: Testing
+   Good practice to test using multiple browsers and devices


#Pages included#
layouts/
+   _home.jpg_ (home page to navigate to View and Insert pages)
+   _view.jpg_ (view all albums entered, also allows favorite option)
+   _insert.jpg_ (allows inserting new albums)

code/
+   _index.php_ (basic signin page)
+   _home.php_  (Home page - with Nav bar)
+   _view..php_
+   _insert.php_ 
+   _header.php_   (header for all php pages)

#Current Status of Project#
Steps 1 & 2 were completed. Some cleanup would be needed on the user interface sdie for cleaner layout, but the foundation is there.
Step 3: Database and tables would need to be created. 4 large tables should be created (connecting tables not included). These tables include:
+	ALBUM table (holds all ALBUM records)
+	ARTIST table (connected to ALBUM table, holds ARTIST records)
+	TRACK table (also connected to ALBUM table, holds TRACk records)
+	USER table (holds are user and password information, for loggin page)

Step 4: Server-side code is needed. AJAX would potential serve best in Update page, as it would help when users are updating their favorites.

Step 5: Good testing with all devices and browsers, but hopefully by using Bootstrap, this will be easier.
