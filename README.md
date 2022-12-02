# nbcleanse 🚿
A notebook cleaner to end all notebook cleaners

## What?

It's a script that cleans [notebooks](https://jupyter.org/) of "redundant components" like metadata/output and etc.

## Why?

Because notebooks ARE code and whatever goes into your codebase should be as lean as possible.  

Many IDEs which implement a notebook inteface (VScode, Jetbrains and etc.) add data to notebooks files in order to provide some functionalities.  
That said data clutters the notebooks files, is not consistant across IDEs and could even cause failures if it contains dependency assumptions and is committed to a VCS.  

## Why nbcleanse?

Because it's lightweight, configureable and let's you know how many lines of code you've saved your repo - thus making you happy.  

## OK. How?

First Install:
```bash
git pull origin shacharhelmer/nbcleanse # soon to be found on pip
cd nbcleanse && pip install .
```

Then run:
```bash
cd your/notebooks/dir/
nbcleanse
```