# fancy-forms
SCSS library of fancy form elements

<aside>
  <h1 class="center-text">Fancy Forms</h1> 
  <a 
    href="#fancy-radio-buttons"
    class="btn-3 block margin-bottom">
    Fancy Radio Buttons
  </a>
  <a 
    href="#fancy-checkboxes"
    class="btn-3 block margin-bottom">
    Fancy Checkboxes
  </a>
  <a 
    href="#fancy-labels-using-radio-buttons"
    class="btn-3 block margin-bottom">
    Fancy Labels using Radio Buttons
  </a>
  <a 
    href="#fancy-labels-using-checkboxes"
    class="btn-3 block margin-bottom">
    Fancy Labels using Checkboxes
  </a>
</aside>

<main>

   <div class="
                span-12 
                page-padding
                fancy-radio-buttons
                bg-lavender">
      <h2 id="fancy-radio-buttons">Fancy Radio buttons</h2> 
      <p>What is the capital of Norway?</p>
      <div class="span-6 padding-bottom md-screen">
        <input type="radio" id="i-one" name="group-for-fancy-radio-buttons" />
        <label for="i-one">Paris</label>
        <br><br>
        <input type="radio" id="i-two" name="group-for-fancy-radio-buttons" />
        <label for="i-two">Toronto</label>
        <br><br>
        <input type="radio" id="i-three" name="group-for-fancy-radio-buttons" />
        <label for="i-three">Rome</label>
        <br><br>
        <input type="radio" id="i-four" name="group-for-fancy-radio-buttons" />
        <label for="i-four">Oslo</label>
      </div>

      <div class="span-12">
        <pre>
          <code>
            &lt;input 
              type="radio" 
              id="i-one" 
              name="group-for-fancy-radio-buttons" />
            
            &lt;label for="i-one">Paris&lt;/label>
          </code>
        </pre>
      </div>
      
    </div> 
    

    <div class="
                span-12
                page-padding
                bg-yellow">
      <h2 id="fancy-checkboxes">Fancy Checkboxes</h2> 
      <p>Select all of the correct spellings.</p>
      <div class="fancy-checkboxes">
        <input type="checkbox" id="a-one" name="group-for-fancy-checkboxes" />
        <label for="a-one"></label>
        <label for="a-one">Airoplane</label>
        <br><br>
        <input type="checkbox" id="a-two" name="group-for-fancy-checkboxes" />
        <label for="a-two"></label>
        <label for="a-two">Aeroplane</label>
        <br><br>
        <input type="checkbox" id="a-three" name="group-for-fancy-checkboxes" />
        <label for="a-three"></label>
        <label for="a-three">Earlyplane</label>
        <br><br>
        <input type="checkbox" id="a-four" name="group-for-fancy-checkboxes" />
        <label for="a-four"></label>
        <label for="a-four">Airplane</label>
        <br><br>
      </div>

      <div class="span-12">
        <pre>
          <code>
            &lt;input 
              type="checkbox" 
              id="a-one" 
              name="group-for-fancy-checkboxes" />

            &lt;label for="a-one">&lt;/label>
            
            &lt;label for="a-one">Airoplane&lt;/label>
          </code>
        </pre>
      </div>

    </div>


    <div class="
                span-12
                page-padding
                bg-blue">
      <h2 class="fancy-labels-using-checkboxes">Fancy Labels using Checkboxes</h2> 
      <p>Select all of the correct spellings.</p>
      <div class="fancy-labels">
        <input 
          type="checkbox" 
          id="flcb-one" 
          name="group-for-fancy-labels-using-checkboxes" />
        <label 
          for="flcb-one"
          class="span-3 md-screen sm-screen">
          Airoplane
        </label>
        <input 
          type="checkbox" 
          id="flcb-two" 
          name="group-for-fancy-labels-using-checkboxes" />
        <label 
          for="flcb-two"
          class="span-3 md-screen sm-screen">
          Aeroplane
        </label>
        <input 
          type="checkbox" 
          id="flcb-three" 
          name="group-for-fancy-labels-using-checkboxes" />
        <label 
          for="flcb-three"
          class="span-3 md-screen sm-screen">
          Earlyplane
        </label>
        <input 
          type="checkbox" 
          id="flcb-four" 
          name="group-for-fancy-labels-using-checkboxes" />
        <label 
          for="flcb-four"
          class="span-3 md-screen sm-screen">
          Airplane
        </label>
      </div>

      <div class="span-12">
        <h3>Code sample</h3>
        <pre>
          <code>
            &lt;input 
              type="checkbox" 
              id="flcb-one" 
              name="group-for-fancy-labels-using-checkboxes" />

            &lt;label 
              for="flcb-one"
              class="span-3 md-screen sm-screen">
              Airoplane
            &lt;/label>
          </code>
        </pre>
      </div>

    </div>

    <div class="
                span-12
                page-padding
                bg-orange">
      <h2 id="fancy-labels-using-radio-buttons">Fancy Labels using Radio Buttons</h2> 
      <p>Select all of the correct spellings.</p>
      <div class="fancy-labels">
        <input type="radio" id="flrb-one" name="group-for-fancy-labels-using-radio-buttons" />
        <label for="flrb-one" class="span-3 md-screen sm-screen">Paris</label>

        <input type="radio" id="flrb-two" name="group-for-fancy-labels-using-radio-buttons" />
        <label for="flrb-two" class="span-3 md-screen sm-screen">Toronto</label>

        <input type="radio" id="flrb-three" name="group-for-fancy-labels-using-radio-buttons" />
        <label for="flrb-three" class="span-3 md-screen sm-screen">Rome</label>
        
        <input type="radio" id="flrb-four" name="group-for-fancy-labels-using-radio-buttons" />
        <label for="flrb-four" class="span-3 md-screen sm-screen">Oslo</label>
      </RADIO>

      <div class="span-12">
        <h3>Code sample</h3>
        <pre>
          <code>
            &lt;input 
              type="radio" 
              id="flrb-one" 
              name="group-for-fancy-labels-using-radio-buttons" />

            &lt;label 
              for="flrb-one" 
              class="span-3 md-screen sm-screen">
              Paris
            &lt;/label>
          </code>
        </pre>
      </div>

    </div>


</main>
