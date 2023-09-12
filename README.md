# N-dimensional-Nearest-Neighbours
# MY FIRST PROJECT
# NOTE: README FILE NOT COMPLETED YET

<!-- CREDIT: I have used the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. -->

## Summary
Given an (N-1)-dimensional array, return the top M "nearest neighbours" amongst the thousands of previously known arrays, with an estimate (or a range) for the N-th element.

## Background
Product companies (e.g., manufacturers) might use a significant number of parameters (N-1) to describe a single product, whose N-th element is, e.g., its price.
When they receive a new project/product request, they have to generate the whole N-dimensional array for it. In some cases, they have to produce quickly an estimate for the
N-th parameter. This task is daunting if not impossible without an efficient/automated db consultation.
Sometimes, part of the team memory might get lost (e.g., if a member leaves) and a new product code might be released unnecessarily,
just because they couldn't interrogate the db properly and know that the project/product had been requestd before.

* Prevent product duplication in the db, by finding any exact match
* Find M nearest neighbours and return their arrays and N-th element
* Speed up the quotation process providing a price estimate (range, average, median, etc) based on previous quotations

## How is it used?
Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?
Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)
If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">
This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]
   totPop = sum(pop)
   totFish = sum(fishers)
   # write your solution here
   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%
main()
```
## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
## Challenges
What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?
## What next?
How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 
## Acknowledgments
* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
view raw