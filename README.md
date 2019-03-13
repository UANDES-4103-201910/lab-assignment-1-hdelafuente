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