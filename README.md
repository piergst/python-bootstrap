## A bootstrap for a simple python project using **uv** package manager
### Prerequisites
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
