README4.md
=======

![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fniklasskoldmark%2Fgravizo%2Fmaster%2FREADME4.md)

 <details> 
 <summary></summary>
 custom_mark10
   digraph G {
     size ="4,4";
     top1 [shape=box];
   }
 custom_mark10
 </details>


```
![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fniklasskoldmark%2Fgravizo%2Fmaster%2FREADME4.md)
<details> 
<summary></summary>
custom_mark10
  digraph G {
    size ="4,4";
    top41 [shape=box];
    top41 -> parse [weight=8];
    parse -> execute [style=dotted];
    top41 -> init [style=dotted];
    top41 -> cleanup;
    execute -> { make_string; printf};
    init -> make_string;
    edge [color=red];
    top41 -> printf [style=bold,label="4100 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compare41;
  }
custom_mark10
</details>
```
