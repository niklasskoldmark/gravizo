README6.md
=======

![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fniklasskoldmark%2Fgravizo%2Fmaster%2FREADME6.md)

 <details> 
 <summary></summary>
 custom_mark10
 custom_mark10
 </details>


```
![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fniklasskoldmark%2Fgravizo%2Fmaster%2FREADME6.md)
<details> 
<summary></summary>
custom_mark10
  digraph G {
    size ="4,4";
    README6 [shape=box];
    README6 -> parse [weight=8];
    parse -> execute [style=dotted];
    README6 -> init [style=dotted];
    README6 -> cleanup;
    execute -> { make_string; printf};
    init -> make_string;
    edge [color=red];
    README6 -> printf [style=bold,label="README6 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compareREADME6;
  }
custom_mark10
</details>
```
