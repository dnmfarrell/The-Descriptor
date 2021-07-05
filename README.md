# The-Descriptor
A definition of the B5000 information processing system

This PDF was created with the following Bash commands:

```
$ for n in {1..49};do
> printf -v filename "%02d.jpg" "$n"
> wget -q -O "$filename" "http://www.cs.virginia.edu/~robins/BU2/webman_BU_Jan_25_2012/brochure/images/manuals/b5000/descrip/descrip_$n.jpg"
> done
$ convert *.jpg -background white -density 72 -page Letter the-descriptor-b5000-1961.pdf
```
