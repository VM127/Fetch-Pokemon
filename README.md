This program fetches the desired pokemon from the pokemon api 
On clicking the fetch pokemon button, an asynchronous function of fetching the data from api is performed so it is wrapped in async keyword
on receiving a pokemon name, it will search for the pokemon so await function is used since it is a promise and fetched using the fetch function following the url or the api
if the response ok property is false, it will throw a new error object "could not find resource"
but is it is true, it is stored in the data variable in the json format to convert the recieved data into a javascript object 
another variable pokemonSprite is declared to get the sprite object and its front_default attribute to get the image of the pokemon
it is displayed after turning the image property to block 
