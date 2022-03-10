# Spirit Box
Created in collaboration with Christian Alvarado and Julia Stalnaker, Spirit Box is a divination device that determines one's prophecy through photographic cards by utilizing a depth sensing AI kit by OpenCV and an object classification API to determine one's fortune.

## Installation

```
python3 -m pip install -r requirements.txt
```


## Usage

Run the application

Use the DepthAI 4K RGB Cam Input Feed:
```python
python3 main.py -cam
```

Use any of your own MP4 videos as input. Video resolution of 224x224 is recommended for better visualisation output.
```python
python3 main.py -vid [vid path]
```

Use the `-nd` command to not display RGB demo and instead print data to the console
```python
python3 main.py -nd
```
