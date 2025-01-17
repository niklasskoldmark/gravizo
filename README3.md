gravizo
=======

How to include graphviz graphs in github README.md

### New. The indirect way ###
You can use indirect way to refer a source file as graph description. 

Use this syntax: ```![Alt text](https://g.gravizo.com/source/<custom_mark>?<url_source_url_encoded>```). And use html comment or summary tag ```<details><summary></summary></details>``` (you can use html comments but some graphs uses -->) to hide the source followed by your description graph in [DOT syntax](https://en.wikipedia.org/wiki/DOT_(graph_description_language)), [UMLGraph](http://www.umlgraph.org/doc/cd-intro.html), [PlantUML](http://plantuml.sourceforge.net/sequence.html) or [SVG](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics) :

![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fniklasskoldmark%2Fgravizo%2Fmaster%2FREADME3.md)

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
![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2Fniklasskoldmark%2Fgravizo%2Fmaster%2FREADME3.md)
<details> 
<summary></summary>
custom_mark10
  digraph G {
    size ="4,4";
    top7 [shape=box];
    top7 -> parse [weight=8];
    parse -> execute [style=dotted];
    top7 -> init [style=dotted];
    top7 -> cleanup;
    execute -> { make_string; printf};
    init -> make_string;
    edge [color=red];
    top7 -> printf [style=bold,label="700 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compare7;
  }
custom_mark10
</details>
```

This allows to include your graphs in the README and is still readable in a normal text editor.
