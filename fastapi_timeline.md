# Timeline development Springboot Api Rest

api M branch main (4 tests OK) : 

	- GET /api/movies
	
	- GET /api/movies/byId/1
	
	- GET /api/movies/byTitle?t=Spectre
	
	- POST /api/movies (BODY: new movie)

api M branches devm2a (7 tests NOK), devm2b (2 tests NOK), devm2c (tests ok) :
	
	- GET /api/movies/byTitleYear?t=Spectre&y=2015
	
	- GET	/api/movies/byYearRange?mi=1950&ma=1980
	
	- GET /api/movies/byYearRange?mi=1950
	
	- GET /api/movies/byYearRange?ma=1980
	
	- PUT /api/movies (BODY: movie modified)
	
	- DELETE /api/movies/1