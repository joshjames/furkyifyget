# furkyifyget
plugin for plex to allow instant access to yify torrents using the furk api
I really have no idea yet how to code this, the plex plugin uses python which I have limited skills in
however most the actual code will be simply utilising the exisinting API's for the appropriate services.
api's i will be using are.

1. YIFY torrents API. https://yts.re/api
2. Furk API https://www.furk.net/t/api

basic logic will be.
query yify for... all movies? a selection.. top 10..? latest 10 ? or custom query
ideally have a browse ability
on selection of a movie, pass that movie ID with .torrent to furks add torrent 
then check furk for the new updated mp4 file.. some how filter the movie only (largest mp4 ?)
utilise server access (remote ssh maybe) to pass a wget on my plex server of new mp4 file.
force library update in plex.
play new updated file.

this is more ideal than just a init strean play as the file is saved to the plex library.
