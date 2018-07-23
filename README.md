### 4downloader-ultimate
The ultimate open-source[0] image downloader(from 4chan[1]) 

### What is this?
This jar file gives you option to download images from boards with:
1. Direct links to threads i.e. `java -jar 4downloader-ultimate.jar http://boards.4chan.org/g/thread/66855397` (it is important to paste the whole link)
2. RegEx[2] search through given board catalog. i.e. `java -jar 4downloader-ultimate.jar -b g -r ".*/dpt/.*"` will download every thread with title(sub) containing /dpt/ 
3. Files containing following structure(**1 link per line**):
```
link
link
link
...
```
i.e.
```
http://boards.4chan.org/g/thread/66855397
http://boards.4chan.org/g/thread/66851382
http://boards.4chan.org/g/thread/66847028
```
will download 3 links listed in the file (**1 link per line**)
4. Or **ANY** combinations of these!

### Other features
1. Updating files in /new/ directory
2. Silent mode
3. Setting download destination (not prefered, but possible. Takes the Downloads/new or Downloads/permanent prefix)

### Coming next
1. Image database using hashing algorithims
2. Human image classification software

### Any other questions?
1. Run `java -jar 4downloader-ultimate.jar -h` in console in same directory as the 4downloader-ultimate.jar file
2. Tweet @mario662211

#### Adnotations
1. [0] For source code look here: https://github.com/Mario6221/4downloader-ultimate-source
2. [1] According to 4chan API at https://github.com/4chan/4chan-API ToS fullfiling point 3
3. [2] All you need to know about RegEx to use it freely: http://www.vogella.com/tutorials/JavaRegularExpressions/article.html
