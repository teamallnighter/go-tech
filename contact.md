---
title: Contact
date: '2017-11-01T03:00:00.000+00:00'
banner_image: "/uploads/2021/01/01/5bd0bdc12d414-wallpaper-preview.jpg"
heading: Contact Go Tech Foundation
publish_date: '2017-12-01T04:00:00.000+00:00'
show_staff: true
menu:
  navigation:
    identifier: _contact
    weight: 4

---
## Contact Us

<form class="form-template-v3">
  <fieldset class="margin-bottom-md padding-bottom-md border-bottom">
    <div class="text-component margin-bottom-md text-center">
      <h2>Contact us.</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    </div>

    <div class="margin-bottom-xs">
      <div class="grid gap-xxs items-center@md">
        <div class="col-4@md">
          <label class="form-label" for="firstName">First name</label>
        </div>
        
        <div class="col-8@md">
          <input class="form-control width-100%" type="text" name="firstName" id="firstName" required>
        </div>
      </div>
    </div>

    <div class="margin-bottom-xs">
      <div class="grid gap-xxs items-center@md">
        <div class="col-4@md">
          <label class="form-label" for="lastName">Last name</label>
        </div>
        
        <div class="col-8@md">
          <input class="form-control width-100%" type="text" name="lastName" id="lastName" required>
        </div>
      </div>
    </div>

    <div class="margin-bottom-xs">
      <div class="grid gap-xxs items-center@md">
        <div class="col-4@md">
          <label class="form-label" for="inputEmail">Email</label>
        </div>
        
        <div class="col-8@md">
          <input class="form-control width-100%" type="email" name="inputEmail" id="inputEmail" required>
        </div>
      </div>
    </div>

    <div>
      <div class="grid gap-xxs items-center@md">
        <div class="col-4@md">
          <label class="form-label" for="textarea">Textarea</label>
          <p class="text-xs color-contrast-medium margin-top-xxxxs">Optional</p>
        </div>
        
        <div class="col-8@md">
          <textarea class="form-control width-100%" name="textarea" id="textarea"></textarea>
        </div>
      </div>
    </div>
  </fieldset>

  <fieldset class="margin-bottom-md padding-bottom-md border-bottom">
    <div class="text-component margin-bottom-md text-center">
      <h2>Radios and Checkboxes</h2>
    </div>

    <div class="margin-bottom-md">
      <div class="grid gap-xxs items-center@md">
        <div class="col-4@md">
          <div class="form-label">Make a choice</div>
        </div>
  
        <div class="col-8@md">
          <ul class="flex flex-wrap gap-md">
            <li>
              <input class="radio" type="radio" name="radioButton" id="radio1" checked>
              <label for="radio1">Option 1</label>
            </li>
      
            <li>
              <input class="radio" type="radio" name="radioButton" id="radio2">
              <label for="radio2">Option 2</label>
            </li>
          </ul>
        </div>
      </div>
    </div>

    <div>
      <div class="grid gap-xxs items-center@md">
        <div class="col-4@md">
          <div class="form-label">Choose 1+ options</div>
        </div>
  
        <div class="col-8@md">
          <ul class="flex flex-wrap gap-md">
            <li>
              <input class="checkbox" type="checkbox" id="checkbox1">
              <label for="checkbox1">Option 1</label>
            </li>
      
            <li>
              <input class="checkbox" type="checkbox" id="checkbox2">
              <label for="checkbox2">Option 2</label>
            </li>

            <li>
              <input class="checkbox" type="checkbox" id="checkbox3">
              <label for="checkbox3">Option 3</label>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </fieldset>

  <div class="text-right">
    <button class="btn btn--primary">Submit</button>
  </div>
</form>

## Contact Information
{% include address.html %}