{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "<a id='top'></a>\n",
    "\n",
    "# There are Two Projects Here\n",
    "\n",
    "Project 1 has more to do with data visualziation and project 2 with a litle more optimization/hardcore machine learning\n",
    "\n",
    "I think both have validity in the job market and are useful things to learn -- It just depends on what your interests are and what is of interest!\n",
    "\n",
    "# Corian Project (these are mostly just notes): \n",
    "\n",
    "## Pots of Gold\n",
    "\n",
    "1. here's your product wheel and the loss in transition sheets from your random\n",
    "    production plan to one that is optimized. Potentially run through\n",
    "    monte carlo\n",
    "    * traveling salesman\n",
    "    \n",
    "## Hypotheses\n",
    "* we have some anomalies in the data\n",
    "    1. [unusual Next Color Code](#color)\n",
    "    \n",
    "* can we use the sequence of order numbers to isolate those for which we had failed transitions \n",
    "  (i.e. we gave up) and determine the relationship between transition attempts and fail rate?\n",
    "    1. [fail rates](#fail)\n",
    "\n",
    "    \n",
    "\n",
    "    \n",
    "\n",
    "* ### Transition Distributions\n",
    "    1. [distributions](#dist) Let's fill in the cells in the matrix\n",
    "    1. [fraction of transitions explained](#terminate)  When should we terminate a bad transition?\n",
    "    3. [sorted boxplots](#sorted)\n",
    "    2. are we learning as we do the transition more often? [median transition sheets vs number of transits](#transits)\n",
    "\n",
    "\n",
    "[combined data](#combinations)\n",
    "\n",
    "* if we combine with **family labels** what are the transition characteristics for (#2)\n",
    "   \n",
    "    1. inter-family transitions\n",
    "    2. intra-family transitions\n",
    "    3. inter-subfamily transitions\n",
    "    4. intra-subfamily transitions\n",
    "    5. where are we having the most operational upsets in terms of product/family/subfamily\n",
    "\n",
    "\n",
    "* if we combine with **scheduling data**\n",
    "    1. what transitions are being scheduled today and do we have transition data for them\n",
    "\n",
    "\n",
    "* combined with **downtime data**\n",
    "    1. what is the relationship between products on the line and downtime\n",
    "\n",
    "  "
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
   "version": "3.8.1"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
