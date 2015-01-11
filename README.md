# simplelivesubtitles

A very simple HTML based subtitle system for live shows
For now, the whole project is a single HTML file. 
Javascript HTML and CSS are used.

Inside the html body the first list is taken by the javascript.
Each of these items can be displayed one by one.
Control is done using keyboard.
The subtitles can be HMTL formatted and can even contain complex HTML elements.

It was designed for live shows and presentations 
where someone needs to manually press a key to show the next subtitle.
This solution runs light and runs everywhere.

## creating subtitles

The html file needs to be edited manually.
It can be edited with anything which preserves the current structure and scripts.
The only thing that needs to be edited is the orderred list in the document.
For this purpuse the list comes before style and script in the file.
  
    <ol>
      <li>Is this useful?</li>
      <li>No it's just a waste of time</li>
    </ol>

People with no technical knowledge are recommended to use a html editor program.`

## other stuff

I realize that this can be extended into a very good lighweight solution for:

1. subtitles for basically anything in HTML
2. presentations (same cocept but more than just a line of text)
