# Timeline development Springboot Api Rest

front F branch devf1 : 
	
	- list movies + form to add new movie

api M branch main (tests OK) : 

	- GET /api/movies
	
	- GET /api/movies/1
	
	- GET /api/movies/byTitle?t=Spectre
	
	- POST /api/movies (BODY: new movie)

api M branches devm2a (4 tests NOK), devm2b (1 test NOK), devm2c (tests ok) :
	
	- GET /api/movies/byTitleYear?t=Spectre&y=2015
	
	- GET	/api/movies/byYearRange?mi=1950&ma=1980
	
	- GET /api/movies/byYearRange?mi=1950
	
	- GET /api/movies/byYearRange?ma=1980
	
	- PUT /api/movies (BODY: movie modified)
	
	- DELETE /api/movies/1

api M branch dev3a (tests nok), dev3b (tests ok) : new features /api/stars

	- GET /api/artists
	
	- GET /api/artists/1
	
	- GET /api/artists?n=Eastwood
	
	- POST /api/artists (BODY: artist)

api M branch devm4a : new features to handle actors
	- GET /api/movies/1  (now give actors and directors)

	- PUT /api/movies/director?mid=1&did=3

	- PUT /api/movies/actors?mid=1 (BODY: actors)
