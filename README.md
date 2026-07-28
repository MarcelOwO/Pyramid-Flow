# Pyramid Flow

This is a fork of the original [Pyramid Flow Repository](https://github.com/jy0205/Pyramid-Flow)

## Changes to the original repo:

- Adding the option to generate video at 1080p resolution.
  
- Generation will output video files for each intermediate pyramid stage.
  
## Running

To start the gradio server just run 

```sh
uv run app.py
```

This spawns a webserver, in which the user can select to generate either text-to-video or image-to-video.

## Notes

Currently inference at 1080p does not seem to work, the generation process tends to break down in the last stage.

Inference has currently only been test on a arm based macos device.



