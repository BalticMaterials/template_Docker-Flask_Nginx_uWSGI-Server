Poetry - generate requirements.txt without hashes

poetry export --without-hashes --format=requirements.txt > requirements.txt


$export FLASK_APP=run.py
$export FLASK_ENV=development