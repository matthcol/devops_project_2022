# Timeline development Java EE/Spring Api Rest

NB: ne pas oublier de mettre le contexte de l'appli devant les routes suivantes. Exemple http://serveurapi:8080/movieapi/api/movies/1

api M branch main (tests OK) : 

	- GET /api/movies
	
	- GET /api/movies/1
	
	- GET /api/movies/byTitle?t=Spectre
	
	- POST /api/movies (BODY: new movie)
	
api M branches devm2a (4 tests NOK), devm2b (1 test NOK), devm2c (tests ok) :
	
	- GET /api/movies/byTitleYear?t=Spectre&y=2015
	
	- GET /api/movies/byYearRange?mi=1950&ma=1980
	
	- GET /api/movies/byYearRange?mi=1950
	
	- GET /api/movies/byYearRange?ma=1980
	
	- PUT /api/movies (BODY: movie modified)
	
	- DELETE /api/movies/1