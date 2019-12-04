{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Capstone Proposel"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Team members:\n",
    "- **Basmah Alabdulatif**\n",
    "- **Bader Abanmi**"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Problem Statment"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Nowadays, the movie industry is one of the largest entertainment industries. It has been estimated that there are 500000 movies produced up to this point. Lately, Saudi Arabia is moving toward investing on entertainment. Therefore, giving the possibility that soon there will be a Saudi Production Film. In order to move on the right path of creating a blockbuster movie we will analyze what features contribute to a movie being successful. Beside popularity and revenue, the Oscar is the main measure of a movie’s success. Therefore, it is the highest honor in film making. We will collect IMDB  data to create a dataset that will help us achieve our goal."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Data: "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**We collected our data using three sources:**\n",
    "- Scrapping IMDB website.\n",
    "- IMDB API\n",
    "- IMDBPY library\n",
    "\n",
    "Using the previous tools, we created a dataset of more than 10,000 movies produced between 2000 and 2017. For each year we took the top 250 movies in terms of popularity, then we collected randomly 4% of the remaining movies to assure diversity in all respects."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Evaluation method:"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "We will consider the latest Oscar event to be the main evaluation matric by comparing our model’s prediction with actual results."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Time frame:"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "This project is due before 19 December 2019"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Potential challenges:"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- Since we dont know what features contribute to the prediction of the Oscar winners, we are trying to maximize the number of features and examine each. \n",
    "-\tRetrieving data from three different sources is time consuming.\n",
    "-\tThere is no clear documentation for the libraries we are using.\n",
    "-\tWe are not sure that the Oscar is the prime predictor, therefore, we may consider other measures.\n",
    "-\tMost of the features are categorical which needs to be taken into consideration.\n",
    "\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
