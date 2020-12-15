build:
	@pipenv install --deploy

test: test-style build
	@pipenv install --dev
	@pipenv run pytest

test-style:
	@pipenv install --dev
	@pipenv run flake8

run:
	pipenv run ./src/main.

lock:
	@pipenv lock