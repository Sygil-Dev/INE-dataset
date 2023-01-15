This repository contains the data for the INE dataset. The `data` folder contains a list of images and a `.txt` file next to each image containing the tags for the image with the same filename. The filename is made of two things, a hash for the image and a unique id, the full filename for both the image and txt file would be in a format like `hash-uniqueid.ext`.

### About the Imaginary Network Expanded subreddit:
The [Imaginary Network Expanded](https://www.reddit.com/r/ImaginaryBestOf/wiki/networksublist) (INE) is a network of art sharing subreddits ranging from broad in subject to very specific. It is the goal of the INE to share, inspire, discuss and appreciate paintings, drawings, and digital art while maintaining artist credit and source links.

### Tools used:
This dataset was made thanks to the [Hydrus](https://hydrusnetwork.github.io/hydrus/) which was and is still being used to download content from the INE subreddits using subscriptions. Hydrus also allow us to easily add tags to the content we download either manually of by using the [Hydrus PTR](https://hydrusnetwork.github.io/hydrus/PTR.html), thanks to this we can reduce the amount of work needed to make this dataset.

In order to easily explorer the dataset it is recommended to use either Hydrus itself and import the images to it or use our HuggingFace space for the [INE-dataset-explorer](https://huggingface.co/spaces/Sygil/INE-dataset-explorer).
