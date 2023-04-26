All thanks to Adrian Rosebrock (from [pyimagesearch](https://www.pyimagesearch.com/)) for making
great tutorials. This project is inspired from his blog: [Ball Tracking with OpenCV](https://www.pyimagesearch.com/2015/09/14/ball-tracking-with-opencv/). I have included the author's code and the one i wrote my self as well.

## **Key Points**
1. Steps involved:
    1. Detect the ball in the image
    2. Track the ball as it moves around in the video. Draw it's previous locations.
    
2. HSV color space is used to detect the green ball. Hence we convert the input RGB image to HSV color space.
3. Finds the centroid (center of the circular ball) using moments.
4. Stores the previous ball location in a queue.
5. The script is suitable for real time tracking as it has a very good frame rate (>32 FPS).
6. The ball can be partially occluded and our script will still successfully track the ball.
