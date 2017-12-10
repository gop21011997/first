# first
code vto run multiply.cpp

// multiply.cpp
#include<iostream.h>
int main(){
float x ,y,z;
cout <<"enter two numbers :"
cin >>x>>Y;

z=multiply(x,y);
cout <<"result ="<<z;
rerturn 0;
}
int multiply(float x, float y)
{
    return x * y;
}
//index.html
<html>
<textarea id="output_area" style="width:100%; height:50%"></textarea>
<script>
  function output(text) {
    document.getElementById("output_area").append(text + "\n\n");
  }
  var Module = {
    'print': function (text) {
      output("print\n" + text);
    };
    'printErr': function (text) {
      output("printErr\n" + text);
    };
  };
</script>
<script src="multiply.js"></script>
</html>
// build.sh or build.bat
em++ -s WASM=1 # ...
