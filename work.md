---
title: Work
layout: landing
description: Below you can see some of the projects I've worked in and some of my hobbies
image: assets/images/work.jpeg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Comparison between MongoDB and RDBMS databases</h2>
		</header>
		<p>This work shows advantages and disadvantages of using Postgres or MongoDB.
		The main purpose is to let you know the great potential of NoSQL databases when you have to process big data volumes.</p>

		<table>
          <tr>
            <th>MongoDB</th>
            <th>PostgreSQL</th>
          </tr>
          <tr>
            <td>NoSQL</td>
            <td>SQL</td>
          </tr>
          <tr>
            <td>JSON</td>
            <td>SQL</td>
          </tr>
        </table> 

<p>Main examples of queries using both MongoDB and Postgres are:</p>
		<table>
          <tr>
            <th>MongoDB</th>
            <th>PostgreSQL</th>
          </tr>
          <tr>
            <td>Not Required</td>
            <td>CREATE TABLE users (user_id VARCHAR(20) NOT NULL,age INTEGER NOT NULL,status VARCHAR(10));</td>
          </tr>
          <tr>
            <td>db.users.insert({ user_id: "bcd001", age: 45, status: "A" })</td>
            <td>INSERT INTO users(user_id,age,	status)VALUES ('bcd001',45,"A");</td>
          </tr>
          <tr>
            <td>db.users.find()</td>
            <td>SELECT * FROM users;</td>
          </tr>
          <tr>
            <td>db.users.update({ age: { $gt: 25 } },{ $set: { status: "C" } },{ multi: true })</td>
            <td>UPDATE users SET status = 'C' WHERE age > 25;</td>
          </tr>
        </table> 
        <ul class="actions">
					<li><a href="https://github.com/rferran/MongoVsPostgres/blob/master/README.md" class="button">Learn more</a></li>
		</ul>
</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="https://www.instagram.com/p/B5ZduhDpV1y/" class="image">
			<img src="{% link assets/images/sunset.JPG %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Photography</h3>
				</header>
				<p>Since I was young, I like photography and wherever I go I try to capture the most beautiful place. 
				Here you will see some of my favourite shots.</p>
			</div>
		</div>
	</section>
	<section>
		<a href="https://www.instagram.com/p/B80Vm5eJeSH/" class="image">
			<img src="{% link assets/images/atocha.JPG %}" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Travelling</h3>
				</header>
				<p>It's also one of my favourite hobbies. I love learning new cultures and visiting cities. </p>
			</div>
		</div>
	</section>
	<section>
		<a href="https://www.instagram.com/p/B6u51QSJMd9/" class="image">
			<img src="{% link assets/images/sunsetSitges.JPG %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Sunsets</h3>
				</header>
				<p>One of the most beautiful scenes of the day. Not only relaxing but also exciting.</p>
			</div>
		</div>
	</section>
</section>

</div>
