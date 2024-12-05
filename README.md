└── project <br>
    ├── docker-compose.yml <br>
    ├── mysql <br>
    │   ├── data <br>
    │   └── init.sql <br>
    ├── nginx <br>
    │   ├── default.conf <br>
    │   └── index.html <br>
    └── php <br>
        ├── Dockerfile <br>
        └── process_form.php <br>
Create main directory as project <br>
Inside project create 3 sub directory as nginx, php, mysql <br>
Put all the files as per directory name <br>
create directory inside mysql named as data and leave it blank <br> (after we are going to bind the data directory as a volume)
Open docker-compose file and check the all paths are correctly written in the file <br> (check the spacing)
Then build the file and hit IP to browser <br>
