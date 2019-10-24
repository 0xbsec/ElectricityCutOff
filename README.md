## What

In lebanon we have regular electricity cut offs, this app show as a toolbar tool to tell wether it's electricity is currently on or off (using a backup generator).

Based on 3 ranges: (you have ability to select ranges)

## ScreenShots



## Development

- Install requirements: `pip3 install -r requirements.txt`.
- Package:
  - `fbs freeze`
  - `fbs installer`
- Run tests: `python3 -m unittest discover -s src/main/python/ -p 'test_*.py'`
- Run linter: `black src/main/python/`