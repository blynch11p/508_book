# Search

Need label on search box for screen readers to know what they are looking at.

Add an `HREF` anchor to the search results page and the form to skip all the navigation etc.

```HTML
<div class="SEARCH">
<form name="Skills_Search" action="searchResults.html#MAINCONTENT">
<label for="search2">Search</label>
<input name="search2" id="search2" />
<input type="submit" value="Search" />
</form>
</div>
```
To hide the word “Search” just add to the CSS class used for the skip navigation.

