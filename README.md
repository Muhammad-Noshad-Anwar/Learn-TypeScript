<h1>In TypeScript, there are three main types of variables:</h1>
<h3>In TypeScript, variables are declared using the let, const, and var keywords.</h3>
<hr>

  <p><dl>
    <dt><h2>01. let</h2></dt>
    <dd><em>In TypeScript, let is used to declare variables that can be reassigned.</em></dd>
    <p>syntax</p>
    <p>let variableName: type = value;</p>
    <p>example</p>
    <p>let name: string = 'John';</p>
  </dl>
  <h3>best practice</h3>
  <p>
    1. Use let for mutable variables. <br>
    2. Use meaningful variable names. <br>
    3. Use type annotations for clarity. <br>
    4. Avoid redeclaring let variables in the same scope <br>
  </p>
  <hr>
   
  <p><dl>
    <dt><h2>02. const</h2></dt>
    <dd><em>In TypeScript, const is used to declare constant variables that cannot be reassigned.</em></dd>
    <p>syntax</p>
    <p>const variableName: type = value</p>
    <p>example</p>
    <p>const digits : number = 3.14;</p>
  </dl>
  <h3>best practice</h3>
  <p>
    1. Use const for immutable variables. <br>
    2. Use meaningful variable names.<br>
    3. Use type annotations for clarity. <br>
    4. Avoid using const for variables that may change.<br>
  </p>
  <hr>
  
   <p><dl>
    <dt><h2>03. var</h2></dt>
    <dd><em>In TypeScript, var is used to declare variables, but it's generally recommended to avoid using var in favor of let and const.</em></dd>
    <p>syntax</p>
    <p>var variableName: type = value;</p>
    <p>example</p>
    <p>var name: string = 'John';</p>
  </dl>
  <h3>best practice</h3>
  <p>
    1. Function scope: var variables are scoped to the nearest function. <br>
    2. Mutable: var variables can be reassigned.<br>
    3. Hoisted: var variables are moved to the top of their scope.<br>
    4. Redefinable: var variables can be redeclared in the same scope.
  </p>
  <hr>

