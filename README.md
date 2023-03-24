<h1 align="center">Track Error Tickets</h1>
<p align="center">
  Report errors and track the errors. Assign a person to the ticket and close the ticket when it gets corrected.
</p>
<img src='' alt=''>

<h2>How It's Made:</h2>
<p align="left">
  <strong>Tech Used:</strong>HTML, JavaScript, Bootstrap, Chance.js
</p>
<p align="left">
  Using local storage to store the tickets, this app creates a list of the tickets onto the page with a unique ID using.
</p>

<h2>Lessons Learned:</h2>
<p align="left">
  Building this taught me how to add into local storage and from that storage add in the infomation that was inserted. I have learned how to use Chance.js to create a unique ID in order to differentiate the different tickets, while trying to use Chance.js I found out about mixed content. When I first added Chance.js it went well then I deployed it live and got a mixed content error which prevented the tickets from saving, after trying several different things and a few searches, turns out I had the wrong src link("http://chancejs.com/chance.min.js") and had to switch it for the correct one("https://cdn.jsdelivr.net/npm/chance@1.1.7/chance.min.js"). Later I plan to add the information into a database to see the information anywhere.
</p>
