"# nodejs-filesystem" 
http://localhost:4000/
http://localhost:4000/getTextFiles

The provided Node.js and Express application offers two API endpoints. The first endpoint, accessed through /, generates a text file within a designated folder named text_files. The file's content consists of the current timestamp, and its filename reflects the current date and time. The second endpoint, accessible via /getTextFiles, retrieves all text files stored within the text_files folder, returning their filenames as a JSON response.