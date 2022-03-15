# my-recipes
This is my personal HTML cookbook. You can add some recipes by pull requests.<br/>
<ol>
  <li>Use this HTML or CSS code to make your recipe.<br/>
    <strong>HTML: </strong>
    <code>&lt;link rel=&quot;stylesheet&quot; href=&quot;../assets/default.css&quot;/&gt;</code><br/>
    <strong>CSS: </strong>
    <code>@import url("../assets/default.css");</code><br/>
    Note that the used CSS file using English classes but with Indonesian <code>content</code>s, so you have to localize it :)
  </li>
  <li>
    Put the recipe photo with the name default.jpg inside a <code>div</code> element.
  </li>
  <li>
    Use these classes to build the layout:
    <ul>
      <li><code>recipe-title</code></li>
      <li><code>recipe-image</code></li>
      <li>
        <code>recipe-details</code>
        <ul>
          <li><code>recipe-details-portion</code></li>
          <li><code>recipe-details-time</code></li>
          <li><code>recipe-details-cal</code></li>
        </ul>
      </li>
      <li><code>recipe-ingredients</code>*</li>
      <li><code>recipe-steps</code>*</li>
    </ul>
    <div>* Use ID to distinguish each ingredients/steps and add <code>#your-id::before</code> CSS rule and assign "content" property to customize the title.</div>
  </li> 
</ol> 
  
