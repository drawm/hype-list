Hype List
===

Low tech way to keep track and automatically decluther your reading list
* Add links and assign them ratings.
* When you feel like reading, get the list of top links in your list
* After reading the content of a link, remove it from the list
* If you feel like you can't catch up, trim your list to archive half of your links

> Disclamer
> This is mean to be a starting point for a project with better UX
> While the scripts are very usable, they are not accessible (terminal only, no use of $PATH, etc)


```
# Add a new link
./add [rating] [link]

# Remove link
./remove [link]

# hype-list
./hype-list [number of links, defaults to 3]

# Archive half of all links
# Use it if you feel you can't catch up, deleted links will be archived
./trim
```


