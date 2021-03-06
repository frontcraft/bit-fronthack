## Form input states


Input states to communicate the error, success or disabled input. Contains
styles for help text and addon.

### Markup:
```
<form class="form">

  <div class="form__item has-success">
    <label class="form__label" for="textInput">Input with success</label>
    <input class="form__input" name="textInput" type="text" />
    <div class="form__addon"><i class="icon icon--ok"></i></div>
    <span class="form__help">Help text</span>
  </div>

  <div class="form__item has-success">
    <span class="form__label">Checkboxes/Radios with success</span>
    <label class="form__radio">
      <input type="radio" name="radio" value="option1" /> Option 1
    </label>
    <label class="form__radio">
      <input type="radio" name="radio" value="option2" /> Option 2
    </label>
  </div>

  <div class="form__item has-error">
    <label class="form__label" for="textInput">Input with error</label>
    <input class="form__input" name="textInput" type="text" />
    <div class="form__addon"><i class="icon icon--x"></i></div>
    <span class="form__help">Help text</span>
  </div>

  <div class="form__item has-error">
    <span class="form__label">Checkboxes/Radios with error</span>
    <label class="form__radio">
      <input type="radio" name="radio" value="option1" /> Option 1
    </label>
    <label class="form__radio">
      <input type="radio" name="radio" value="option2" /> Option 2
    </label>
  </div>

  <div class="form__item" disabled>
    <label class="form__label" for="textInput">Disabled input</label>
    <input class="form__input" name="textInput" type="text" />
    <span class="form__help">Help text</span>
  </div>

  <div class="form__item" disabled>
    <span class="form__label">Disabled Checkboxes/Radios</span>
    <label class="form__radio">
      <input type="radio" name="radio" value="option1" /> Option 1
    </label>
    <label class="form__radio">
      <input type="radio" name="radio" value="option2" /> Option 2
    </label>
  </div>

</form>
```