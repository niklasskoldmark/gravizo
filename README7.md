README7.md
=======

![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fniklasskoldmark%2Fgravizo%2Fmaster%2FREADME7.md)

 <details> 
 <summary></summary>
 </details>


```
![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fniklasskoldmark%2Fgravizo%2Fmaster%2FREADME7.md)
<details> 
<summary></summary>
custom_mark10
  digraph G {
    size ="4,4";
    README7 [shape=box];
    README7 -> parse [weight=8];
    parse -> execute [style=dotted];
    README7 -> init [style=dotted];
    README7 -> cleanup;
    execute -> { make_string; printf};
    init -> make_string;
    edge [color=red];
    README7 -> printf [style=bold,label="README7 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compareREADME7;
  }
custom_mark10
</details>
```
