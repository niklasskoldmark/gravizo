README4.md
=======

![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fniklasskoldmark%2Fgravizo%2Fmaster%2FREADME5.md)

 <details> 
 <summary></summary>
 custom_mark10
   digraph G {
   }
 custom_mark10
 </details>


```
![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fniklasskoldmark%2Fgravizo%2Fmaster%2FREADME5.md)
<details> 
<summary></summary>
custom_mark10
  digraph G {
    size ="4,4";
    top51 [shape=box];
    top51 -> parse [weight=8];
    parse -> execute [style=dotted];
    top51 -> init [style=dotted];
    top51 -> cleanup;
    execute -> { make_string; printf};
    init -> make_string;
    edge [color=red];
    top51 -> printf [style=bold,label="top51 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compare51;
  }
custom_mark10
</details>
```
