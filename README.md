# ez-d3-graphs

Easy wrappers to help generate lovely graphs with d3 and svg.

See examples: http://mikejestes.github.com/ez-d3-graphs/

## Generate new random data
    make clean
    make

## Simple Examples
    var dataArray = [4,9,7,2,1,2,6,4,8,9,3];

    var graph = new ezD3Graphs.ComboGraph('#element', 300, 100);
    graph.add( new ezD3Graphs.BarGraph(dataArray) );
    graph.render();
