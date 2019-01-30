# jquery-load
<h3>How to load one Page Content into another page using JQuery</h3>

<h3>.load()</h3>

<p><strong>Description: </strong>Load data from the server and place the returned HTML into the matched element.</p>
<p><strong>Syntax: </strong>.load( url [, data ] [, complete ] )</p>
<br>
<p><b>url</b>
<br>
<span>Type: </span>String
<br>
A string containing the URL to which the request is sent.
<br>
<p><b>data</b>
<br>
<span>Type: </span>PlainObject or String
<br>
<p><b>complete</b>
<br>
<span>Type: </span>Function( String responseText, String textStatus, jqXHR jqXHR )
<br>
A callback function that is executed when the request completes.
<br>
</p>
<br>

<p><strong>step 1:</strong> Download th project</p>
<p><strong>step 2:</strong> Run index.html file</p>
<p><strong>step 3:</strong> It will show what are the content in sample.html in index.html</p>
<p><strong>eg:</strong>
<br>
$(function(){
      $("#includedContent").load("sample.html"); 
    });
    <br>
</p>
