export collections from mongo DB into json file

        mongoexport -d "database_name" -c "collections_name" -o "json_file_name"
    
Import collection from json file into mongo DB

        mongoimport -d "database_name" -c "collections_name" "json_file_name"
