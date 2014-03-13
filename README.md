Get-YouTube-ID
==============

Get The YouTube Video ID from ANY YouTube URL

//Just use these lines of JavaScript Code:

var rawURL = "https://www.youtube.com/watch?v=Qi14A20MJbE";
var youtubeIndex = rawURL.indexOf("watch?v=");
var junkCode = 8;
var youtubeCode = rawURL.substring(youtubeIndex + junkCode);

document.writeln(youtubeCode);
