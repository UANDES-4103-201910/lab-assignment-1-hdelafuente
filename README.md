# lab-assignment-1
Base project for lab assignment 1

## 1. HTML and site structure
The site uses 3 tables, one for the top navbar, another for the news feed and the last one for the footer.

The following tags are used to structure how the heading will be displayed:
```
<table> <!-- Table tag iteslf, used to create the table-->
	
	<tbody> <!-- Defines the table body, here is where the content will be placed -->
	
		<tr class="some class" id="some id"> <!-- Table row -->
	
			<td class="some class again"> <!-- Cells for the row, used to separate content -->
				
				<span class="rank"> This tag is used to group inline elements in the document </span>
			
			</td> 
			
			<td class="another class"> 
				<center> <!-- used to center-align text -->
					<a href="link to some place in the internet"> This tag is used for links </a>
				</center>
			</td>

			<td class="and yet another class">
				<a href="link to the article itself"> article title </a>
				<span> article source </span>
			</td>
	
		</tr>
	
		<tr class="spacer"></tr> <!-- A spacer between news headings -->
	
	</tbody>

</table>
```

## 2. Downloaded files by the browser
When the user reaches the site, the browser will download some file in order to show the page the way it was intended by the developer, for __https://news.ycombinator.com/__ are the following:

* (index) : HTML code for the site.
* hn.js?ok3V8Gydw5sSOFppv3U2 : Javascript file to provide interactivity to the site.
* news.css?ok3V8Gydw5sSOFppv3U2 : Css file to provide style.
* And some .gif files just for esthetics.

## 3. XHR request
An XHR (XMLHttpRequest) is and API in form of an object whose methods are used to transfer data between the web server and the web browser,  these objects are handled by the JS environment of the web browser. So these files are loaded when the JS files are loaded.

## 4. SSL server certificate 
To connect securely to web site, the web browser has to download a certificate, more specifically an SSL Server Certificate in order to ensure a secure connection, SSL is a security protocol used to secure data between 2 machines using encryption.

The SSL certificate emitted for the connection is provided by:

```
Common Name (CN)	COMODO RSA Domain Validation Secure Server CA
Organization (O)	COMODO CA Limited
Organizational Unit (OU)	<Not Part Of Certificate>
```

and the exiparation date is the following:
```
Issued On	Thursday, August 21, 2014 at 8:00:00 PM
Expires On	Wednesday, August 21, 2019 at 7:59:59 PM
```
