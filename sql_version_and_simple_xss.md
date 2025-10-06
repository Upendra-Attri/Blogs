# SQL Version Enumeration + Reflected XSS — Concepts, Failures, Fixes

INTRODUCTION:

Today I did two portswigger labs one is “**Lab: Reflected XSS into HTML context with nothing encoded**” and Another One is “**Lab: SQL injection attack, querying the database type and version on MySQL and Microsoft” .**

Date: 6/10/2025

Time: 11:30 pm

### **Lab 1: Reflected XSS into HTML context with nothing encoded**

This lab is very basic and i as it is mentioned in its description **“This lab contains a simple reflected cross-site scripting vulnerability in the search functionality.”** 

I access the lab and just run the javascript in the search field and it solved very quickly

### **Lab 2: SQL injection attack, querying the database type and version on MySQL and Microsoft**

This lab is not basic as the first one in it we should use our database and injection skills so we should get the right data and as it is mentioned in it description like it has the sql vuln in categories function so first i use the normal union statement to check which syntax is valid like

 ?categories=’ OR 1=1 — if this payload doees not give any error then we will do the union attack but it trough an internal error and i dont know why and ten i use several methods and  search on te internet according ton syntax and ten find that in some databases engines we should add sapces after comments so it will parse correctly and after 20 minutes of research we did this lab and learn that the syntax learning should be very strong like and we should know that how a parser will parse this command .

thats it for today guys we will meet tommorow again with more labs and hacking stuff 

bye…………………….
