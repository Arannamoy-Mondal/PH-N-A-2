<ul id="lang">
<li><a href="#bangla">Bangla</a></li>
<li><a href="#english">English</a></li>
</ul>
<a href="#lang">Language</a>
<ol id="bangla">
<li>
<h3>PostgreSQL কি? </h3>

- <h3>PostgreSQL একটি ওপেন সোর্স ডেটাবেস ম্যানেজমেন্ট সিস্টেম। এর প্রধান বৈশিষ্ট্যগুলো হলো: এটি সম্পূর্ণ বিনামূল্যে এবং ওপেন সোর্স। এটি ACID (Atomicity, Consistency, Isolation, Durability) কমপ্লায়েন্ট, যার মানে হলো এটি ডেটার নির্ভরযোগ্যতা ও নিরাপত্তা নিশ্চিত করে। এতে রয়েছে শক্তিশালী ডেটা ইন্টেগ্রিটি সাপোর্ট, যার মাধ্যমে ডেটা ঠিকঠাক ও নির্ভুল থাকে। এটি বিভিন্ন এক্সটেনশনের সাথে কমপ্যাটিবল—যেমনঃ PL/pgSQL, Python, ইত্যাদি। এটি কমন ব্যাকএন্ড টেকনোলজি যেমন Node.js, Django ইত্যাদির সাথে সহজেই কাজ করে। </h3>
</li>
<li>
<h3>PostgreSQL-এ Primary Key এবং Foreign Key ধারণাগুলি ব্যাখ্যা।</h3>

- <h3>Primary Key হলো একটি টেবিলের প্রতিটি রেকর্ডের জন্য একটি অনন্য শনাক্তকারী। এটি নিশ্চিত করে যে প্রতিটি সারি অনন্যভাবে চিহ্নিত করা যাবে এবং এতে অবশ্যই ইউনিক ও নাল না হওয়া মান থাকতে হবে। প্রতি টেবিলের শুধু একটি Primary Key থাকতে পারে। Foreign Key হলো একটি টেবিলের একটি কলাম (বা একাধিক কলামের সেট), যা অন্য একটি টেবিলের Primary Key-কে রেফার করে। এটি দুইটি টেবিলের মধ্যে সম্পর্ক গড়ে তুলতে ব্যবহৃত হয়। Foreign Key গুলো ইউনিক হতে হবে না, কিন্তু এগুলোকে অবশ্যই রেফার করা টেবিলের একটি বৈধ Primary Key মানের সাথে মিলতে হবে।</h3>
</li>

<li>
<h3>VARCHAR এবং CHAR ডেটা টাইপের মধ্যে পার্থক্য কী?</h3>

- <h3>VARCHAR(n) এ ব্যবহারকারী চাইলে n অক্ষর পর্যন্ত সংরক্ষণ করতে পারেন, কম ব্যবহার করে। CHAR(n) এর একটি নির্দিষ্ট দৈর্ঘ্য রয়েছে, যার অর্থ এটি সর্বদা ঠিক n অক্ষর সংরক্ষণ করে।</h3>
</li>

<li>
<h3>Explain the purpose of the WHERE clause in a SELECT statement.</h3>

- <h3>WHERE  এর মূল উদ্দেশ্য হলো নির্দিষ্ট শর্তের উপর ভিত্তি করে ডেটা নির্বাচন করা বা বের করা। অর্থাৎ, এটি ডেটাবেজ থেকে কেবলমাত্র সেই রেকর্ডগুলোকে ফিরিয়ে আনে যা নির্দিষ্ট শর্ত পূরণ করে।</h3>
</li>

<li>
<h3>LIMIT এবং OFFSET কীসের জন্য ব্যবহৃত হয়?</h3>

- <h3>LIMIT ব্যবহার করা হয় ফলাফল থেকে নির্দিষ্ট সংখ্যক সারি (rows) ফেরত দেয়ার জন্য, সাধারণত শুরু থেকে। OFFSET ব্যবহার করা হয় প্রথম থেকে নির্দিষ্ট সংখ্যক সারি স্কিপ (বর্জন) করার জন্য, তারপর বাকিগুলো দেখানোর জন্য।
</h3>
</li>
</ol>
<a href="#lang">Language</a>
<ol id="english">
<li>
<h3>What is PostgreSQL?</h3>

- <h3>PostgreSQL is an open-source relational database management system (RDBMS). Its key features include:It is completely free and open-source.It is ACID-compliant (Atomicity, Consistency, Isolation, Durability), ensuring reliable and secure transactions.It provides strong data integrity, which helps maintain accurate and consistent data.It supports multiple extensions, such as PL/pgSQL, Python, and more.It works well with popular backend frameworks like Node.js and Django.</h3>
</li>
<li>
<h3>Explain the Primary Key and Foreign Key concepts in PostgreSQL.</h3>

- <h3>A Primary Key is a unique identifier for each record in a table. It ensures that each row can be uniquely identified and must contain unique, non-null values. Every table can have only one primary key. A Foreign Key is a column (or set of columns) in one table that refers to the Primary Key in another table. It is used to create a relationship between two tables. Foreign keys do not have to be unique, but they must match a valid primary key value in the referenced table.</h3>
</li>
<li>
<h3>What is the difference between the VARCHAR and CHAR data types?</h3>

- <h3>VARCHAR(n) has a flexible length, meaning the user can store up to n characters, using fewer if desired. In contrast, CHAR(n) has a fixed length, meaning it always stores exactly n characters.</h3>
</li>
<li>
<h3>Explain the purpose of the WHERE clause in a SELECT statement.</h3>

- <h3>The main purpose of the WHERE clause is to retrieve data based on specific conditions.</h3>
</li>
<li>
<h3>What are the LIMIT and OFFSET clauses used for?</h3>

- <h3>LIMIT is used to return a specific number of rows from the beginning of the result set. OFFSET is used to skip a specified number of rows before starting to return rows.For example, LIMIT n OFFSET n will skip the first n rows and then return the next n rows.</h3>
</li>
<ol>