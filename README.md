## A bootstrap for a simple python project with tests
### Prerequisites
This project uses *uv* package manager.
Before you begin, ensure you have met the following requirements:
##### Arch linux : 
```
sudo pacman -s python-uv
```
### Usage
Clone the project and run the following command to update dependencies :
```
uv sync
``` 
### Running tests
``` 
pytest
# or
uv run pytest
```

### About project name
Remember that *uv* requires a match between the project name (in *pyproject.toml*) and the directory name. 
If you change one, make sure to update the other accordingly.
