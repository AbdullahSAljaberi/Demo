.PHONY: install run lint

all: install run lint

install:
	@echo "Upgrading pip..."
	@pip install --upgrade pip
	@echo "Installing dependencies..."
	@pip install -r requirements.txt
	@echo "Installation complete."

run:
	@echo "Running script..."
	@python hello.py

lint:
	@echo "Linting script..."
	@flake8 hello.py
	@echo "Linting complete."
