# Shared hosting installation guide

## Options you can choose

For **newbies** we offer a completely ready to use solution. If you are not geek much you can just use this option with all the difficult tech stuff made by ourselves. All you need to have is PHP version equal or higher then 5.3, any domain name you want to use. And a little bit of courage :)

Minimal requirements (**for newbies**):
* Apache >= 2.*
* PHP version >= 5.3, with installed modules: PDO, PDO_MYSQL
* Any domain name

Ready for more? If you are one of those bearded high-skilled dudes and want to use **your own search engine**, and **data base**, we do not limit you. Just choose the Advanced mode and get ready to make it! Advanced requirements (for **geeks**):
* Apache >= 2.*
* PHP version >= 5.3, with installed modules: PDO, PDO_MYSQL
* Any domain name
* Sphinx engine >= 2.1
* MySQL >= 5.*

## Installation steps

### Step 1. Download source.
Download the latest engine version at openbay.isohunt.to or at GitHub project web page.

### Step 2. Upload source to a chosen hosting.
Upload the source code to desirable web hosting following the web hosting guide (in a common case there is a CPanel tool) or just use FTP

### Step 3. Unzip source to the hosting folder (optional)
This step is quite optional. It depends on your web hosting. Some hostings can unzip sources automatically, some of them allows you to make it manually.

### Step 4. Set hosting environment (optional)
*Apache*
This option **is available by default** in the original source pack. You can see it at `conf/example.htaccess`

*Nginx* 
This config is available in the original source pack at `/conf/example.nginx.conf`

*Sphinx* (**advanced mode**)
[Instruction here](https://github.com/isohuntto/openbay/wiki/sphinx)

*MySQL* (**advanced mode**)
Before the wizard running you need to create a data base, the scheme of the data base will be created by the wizard. Dump here `/src/protected/data/schema.mysql.sql`

### Step 5. Wizard
Congrats! Now you can open your domain name with any browser and follow the guide provided there. By default you will need to put the page title which will appears on all of your webpages.

## Was not useful for you?
Have more to say? Feel free to fork our article and edit or add whatever you want.