# Common Resources for NVSL Papers

You should only make changes to the contents of this repo if they useful across other, future papers we will write.

If you need to modify something for your specific paper, you could create a branch or modify `libpaper` to allow an graceful override in your paper.

##  What Gets Built

By default, `Make.rules` builds `paper.pdf` but you can have it build anything else by setting `PDF_TARGETS` in your paper's make file.