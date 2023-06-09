<!DOCTYPE html>
<html>
<body>
  <h1>Delivery Agent Problem</h1>
  <h2>Problem Definition</h2>
  <p><strong>Pick the order up and find the minimum cost path to the destination, then deliver the order to the customer.</strong></p>
  <h2>Environment Type</h2>
  <p><strong>Static</strong></p>
  <h2>Agent Type</h2>
  <p><strong>Pro-active</strong></p>
  <h2>PEAS</h2>
  <ul>
    <li><strong>P:</strong> Cost (minimize cost), Safely deliver the order, Check order integrity, Safety of the agent, Number of orders delivered per hour.</li>
    <li><strong>E:</strong> Roads</li>
    <li><strong>A:</strong> Arms, Wheels</li>
    <li><strong>S:</strong> GPS, Infrared, Camera</li>
  </ul>
  
  <h2>A* Algorithm</h2>
  <p><strong>Using A* algorithm the agent looks for the best path to take by minimizing f(n)= total cost + hueristic value from a dynamic initial state to a dynamic goal state from the states in the following graph (which can be changed).</strong></p>
  <p><strong>The hueristic function finds the path with the minimum number of steps to the goal state.</strong></p>
</body>
</html>

![foto grid](https://github.com/reem010/DeliveryAgent/assets/108128985/70699098-faa3-4bfa-9836-f0c838afafa9)
