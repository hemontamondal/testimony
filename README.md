# testimony
This section I have make a testimony slider using html, css &amp; bootstrap.
If I rotate any text then this code will be implement those text.
  
If you want to rotate the text within a single column, you can use CSS to achieve text rotation. Here's an idea using HTML and CSS to rotate text within a single column:

html code:
<div class="container">
  <div class="text">Text 1</div>
  <div class="text">Text 2</div>
  <div class="text">Text 3</div>
</div>

css code:
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.text {
  writing-mode: vertical-rl;
  transform: rotate(180deg);
  padding: 10px;
  border: 1px solid #000;
}
In this example, the writing-mode: vertical-rl; CSS property sets the writing mode to vertical, making the text flow vertically from right to left. The transform: rotate(180deg); property rotates the text by 180 degrees, effectively flipping it vertically. The rest of the CSS is for styling purposes and can be adjusted as needed.
