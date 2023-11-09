access swagger :
cmd -> swag init
cmd -> go run main.go
localfiles : 
http://localhost:8080/swagger/index.html

hostname Hosting :
https://final-project-1-group-5.herokuapp.com/swagger/index.html


- get id by paramter
- post request with JSON, no Form

{
	"name":"Udin",
	"tanggal":"22 Oktober 2022",
	"kegiatan" : [{
                    "nama_kegiatan": "Basket",
                    "jam_kegiatan": "12:00"
    },{
                    "nama_kegiatan": "Sepak Bola",
                    "jam_kegiatan": "12:00"
    }]
}