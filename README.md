# Simple App Upload Files

---
# REST API - Upload File

Basic test endpoint for upload files to server


### Details

    Java Version: 17



### Request
`POST / Upload File`

    curl --location 'http://localhost:8080/file/upload' \ 
    --form 'file=@"C://path-file/img/img.jpg"'
