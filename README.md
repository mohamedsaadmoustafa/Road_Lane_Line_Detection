# Road_Lane_Line_Detection

# 1 read the image
# 2 convert to HSV
# 3 convert to Gray
# 4 Threshold HSV for Yellow and White (combine the two results together)
# 5 Mask the gray image using the threshold output fro step 4
# 6 Apply noise remove (gaussian) to the masked gray image
# 7 use canny detector and fine tune the thresholds (low and high values)
# 8 mask the image using the canny detector output
# 9 apply hough transform to find the lanes
# 10 apply the pipeline you developed to the challenge videos
