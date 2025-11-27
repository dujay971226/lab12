# {Name of the Tool}
written by: [Jay Du, Xiaofeng Li](https://github.com/dujay971226/lab12)

[5 minute] This tutorial covers MyDomains, a PROSITE/ExPASy tool used to generate
schematic diagrams of protein domain architecture. The tool works by allowing users
to input a protein’s length and the positions of its domains or motifs, then
automatically producing a visual map of those features. In virus discovery,
such diagrams help researchers quickly interpret predicted viral proteins,
compare domain arrangements, and identify hallmark domains that support classification
or functional inference.

**Tutorial Objective**: By the end of this tutorial, you will know how to use the 
MyDomains web interface to input a protein sequence, define its domains, and 
generate a clear visual map of its domain architecture.

## Input / Prerequisites
- Any Web Browser
- https://prosite.expasy.org/cgi-bin/prosite/mydomains/
- Sample details for the protein being analyzed

## Output

The output is a graphic image (in PNG format) showing a schematic of the protein: 
a rectangular “bar” representing the full protein, with colored/shaped boxes 
(or shapes) along it corresponding to the domains (or other features) you specified.

![Sample Output](sample_output.png)

You can right-click on the image and choose “Save Image As” to download the PNG.

### 1. Tutorial Instructions

#### 1. Add Domain:

You can add a domain by typing start, stop, shape, color, text in the Domain data text field.  

For example, "100, 200, 2, 4, Domain_1" means adding a domain called Domain_1 
with a shape of 2(sphere), and colored 4(gray), started from 100 to 200.  
![Example: Add Domain](add_domain_example.png){width=50%}

<br>

Supported shapes include:  
![Supported Shapes](shapes.png)  
1. rectangle  
2. Sphere  
3. Pentagon - pointing towards right  
4. Pentagon - pointing towards left  
5. Hexagon - edge points down  
6. Hexagon - angle points down.  

<br>

Supported color include:  
![Supported Colors](colors.png)  
1. Orange  
2. Green  
3. Blue  
4. Grey  

<br>

#### 2. Add Range:


### 2. ...

### N. ...

### Conclusion

That's it! You've used the {Tool Name} to {objective}!

{2-3 sentences which describe the main conclusions of what the reader should come away from this learning}

### See Also:

- [Publication Name](https://www.nature.com/articles/s41586-021-04332-2)
- [Additional useful link](https://web.archive.org/web/19991128125537/http://www.geocities.com/Heartland/Bluffs/4157/hampdance.html)
- [10 best practices for writing documentation](https://www.grammarly.com/blog/developer/10-best-practices-writing-documentation/)
- ...