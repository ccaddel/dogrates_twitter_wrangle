# Wrangle Twitter Data

Real-world data rarely comes clean. Using Python and its libraries, I gathered data from a variety of sources and in a variety of formats, assessed its quality and tidiness, then cleaned it.

The dataset I wrangled (and analyzed and visualized) is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "[they're good dogs Brent](http://knowyourmeme.com/memes/theyre-good-dogs-brent)." WeRateDogs has over 4 million followers and has received international media coverage.

## Workflow Setup

Create a Python environment in Jupyter Notebook with the following packages:
- pandas
- numpy
- requests
- tweepy
- json

## Contribute

Find any typos? Have another resource you think should be included? Contributions are welcome.

First, fork this repository.

![](https://raw.githubusercontent.com/udacity/ud777-writing-readmes/master/images/fork-icon.png)

Next, clone this repository to your desktop to make changes.

`$ git clone https://github.com/ccaddel/dogrates_twitter_wrangle.git`

`$ cd dogrates_twitter_wrangle`

Once you've pushed changes to your local repository, you can issue a pull request by clicking on the green pull request icon.

![](https://raw.githubusercontent.com/udacity/ud777-writing-readmes/master/images/pull-request-icon.png)

Instead of cloning the repository to your desktop, you can also go to `README.md` in your fork on github.com, hit the Edit button (button with the pencil) to edit the file in your browser, then hit the `Propose file change` button, and finally make a pull request.
