# DNA
##### A DNA generator.

#### By Ryan Brown

## Description

This site allows users to enter one helix of DNA and will generate the second.  Also included are articles that users can access via Ajax, meaning you don't have to leave the page in order to see your content!

## Setup

* Clone repository from `https://github.com/browneryan/DNA` and navigate to directory
* Open MAMP (or WAMP) application, select preferences, change document root to the bookstore folder
* A browser window should open upon success (if not click open start webpage), then click the tools tab and select phpMyAdmin
* Choose import tab, click choose file button and select the database zip file within sites/db-backup folder named `dna.sql.zip`
* The database name is `dna`
* Click on database name and select privileges tab, then select add user
* Set username to `admin`, host to `localhost`, and set password to `admin` as well
* Make sure 'grant all privileges on database' is checked, then click go
* Open a new browser tab to `localhost:8888`
* Login username and password are both `admin`

## Technologies Used

* Drupal
* PHP
* AJAX
* SimpleTest

### Legal

Copyright (c) 2016, Ryan Brown

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
