.env configuration hidden

- consider a surrogate key

- consider storing api keys i.e., for gmaps in a cloud vault

- pyodbc library for db connectivity

react js, flask[async] = client (UI), server (data processor)

- configure cors (flask_cors was used)

- npm install google-maps-react 

gcp project - geographgeocodeapikey

- since backend/frontend are separate components - must setup containers separately

- replace flask builtin-wsgi with gunicorn wsgi in Docker config for enabling container-external access to app.