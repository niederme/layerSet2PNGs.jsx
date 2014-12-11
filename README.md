# layerSet2PNGs.jsx – Export Photoshop Groups to PNGs, With File Naming

## Installation

There are a few ways to install and run scripts for Adobe apps. The instructions below are one such way, [but there are other ways.](http://speedscraps.blogspot.com/2010/04/installing-scripts-photoshop.html)

Download the JSX file and place it in a location of your choice. I [made an alias](http://www.dummies.com/how-to/content/basics-of-aliases-in-os-x-mavericks.html) and copied it to my Desktop for easy access.

## Use

This is a helpful tool, but you have to set up your PSD correctly:

1. First, group all of the layers for a given comp in the top-level of the Layers palette.  
*Generally it is helpful to include a full-bleed background layer on the bottom.*  
2. Name this top-level group something — this will be the PNG file name on export. *Spaces will be converted to hyphens, so a group named `1 Home Page` becomes `1-Home-Page.png`.*  
3. You can create as many comp groupings as you need.  
4. When you’re ready to export, your Layers palette should look something like the screenshot below. *There are 7 top-level groups, so the script will export 7 PNGs, using the filenames of each group.*  
![](http://f.cl.ly/items/1q1a442X3b1c2W2N291S/Screen%20Shot%202014-12-11%20at%2011.30.03%20AM.png)  
8. Run the script, by double-clicking the file or alias.  
9. A dialog should pop up… click Yes:  
![](http://f.cl.ly/items/2Z0b013F0x0E243z2D03/Screen%20Shot%202014-12-11%20at%2011.58.30%20AM.png)  
10. The script will run, and export PNGs in the *same folder as your PSD.* When it finishes, you should have 7 flat PNGs. *Note, I used Em dashes in my group names, which is why you see such long dashes.*  
![](http://f.cl.ly/items/1a20133b1O2E0Y1w131k/Screen%20Shot%202014-12-11%20at%2012.13.07%20PM.png)  

That’s all!

## Feedback

Send questions, problems or requests to me on Twitter: [@niederme](https://twitter.com/niederme/).