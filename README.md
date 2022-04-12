# AxleScript
A programming language that compiles to JavaScript.

```
fn hello(name) {
  doc.replace_all("<h1>Hello, " ~ name ~ "!</h1>")
  log("Done!")
}
 hello("There")
 ```
->
```
function hello(name) {
  document.write("<h1>Hello, " + name + "!</h1>");
  console.log("Done!");
}
```
