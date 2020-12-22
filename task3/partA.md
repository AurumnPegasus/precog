## Task A

I could not find a suitable solution for task A. 

Trials:

* Initial trial was done using tabula.py, which was not working for 2 pdfs. Especially the one with multiple pdf where verticle lines were not defined. Therefore I looked for other solutions
* Next I tried working with opencv. What I did was convert the pdf to image using pdf2image library. Next I converted the picture to Black and White. My idea was to then simply convert the BW image into array of 0s and 1s. By this I would be able to identify lines and thus get the region where table is. It had the problem that in one of the pdfs, lines were not straight enough. Therefore it became impossible to get the x and y values