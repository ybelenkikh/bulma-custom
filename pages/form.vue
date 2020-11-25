<template>
  <div class="container">
    <div class="columns">
      <div class="column">
        <p>|.field</p>
        <p class="ml-2">|label.label</p>
        <p class="ml-2">|.control</p>
        <p class="ml-4">|input.input</p>
        <p class="ml-2">|p.help</p>
        <div class="field">
          <label class="label">Label</label>
          <div class="control">
            <input class="input" type="text" placeholder="Text input">
          </div>
          <p class="help">This is a help text</p>
        </div>
      </div>
      <div class="column">
        <p>|.field.has-addons</p>
        <p class="ml-2">|.control</p>
        <p class="ml-4">|input.input</p>
        <p class="ml-2">|.control</p>
        <p class="ml-4">|a.button.is-info{Search}</p>

        <div class="field has-addons">
          <div class="control">
            <input class="input" type="text" placeholder="Find a repository">
          </div>
          <div class="control">
            <a class="button is-info">
              Search
            </a>
          </div>
        </div>
      </div>
      <div class="column">
        <p>|.field.is-grouped.is-grouped-right</p>
        <p class="ml-2">|.control</p>
        <p class="ml-4">|a.button.is-primary</p>
        <p class="ml-2">|.control</p>
        <p class="ml-4">|a.button.is-light</p>
        <div class="field is-grouped is-grouped-right">
          <p class="control">
            <a class="button is-primary">
              Submit
            </a>
          </p>
          <p class="control">
            <a class="button is-light">
              Cancel
            </a>
          </p>
        </div>
        <p>|.field.is-grouped.is-grouped-center</p>
        <div class="field is-grouped is-grouped-center">
          <p class="control">
            <a class="button is-primary">
              Submit
            </a>
          </p>
          <p class="control">
            <a class="button is-light">
              Cancel
            </a>
          </p>
        </div>
      </div>
    </div>
    <div class="columns">
      <div class="column">
        <p>1|.field.is-horizontal</p>
        <p class="ml-3">|.field-label.is-normal</p>
        <p class="ml-5">|label.label{From}</p>
        <p class="ml-3">|.field-body</p>
        <p class="ml-4">|.field</p>
        <p class="ml-5">|input.input</p>
        <p class="ml-4">|.field</p>
        <p class="ml-5">|input.input</p>
        <p>2|.field.is-horizontal</p>
        <p>3|.field.is-horizontal</p>
        <p>4|.field.is-horizontal</p>
        <p>5|.field.is-horizontal</p>
        <p>6|.field.is-horizontal</p>
        <p>7|.field.is-horizontal</p>
        <div class="field is-horizontal">1
          <div class="field-label is-normal">
            <label class="label">From</label>
          </div>
          <div class="field-body">
            <div class="field">

                <input class="input" type="text" placeholder="Name">
                <span class="icon is-small is-left">
                  <i class="fas fa-user"></i>
                </span>

            </div>
            <div class="field">

                <input class="input is-success" type="email" placeholder="Email" value="alex@smith.com">
                <span class="icon is-small is-left">
                  <i class="fas fa-envelope"></i>
                </span>
                <span class="icon is-small is-right">
                  <i class="fas fa-check"></i>
                </span>

            </div>
          </div>
        </div>
        <div class="field is-horizontal">2
          <div class="field-label"></div>
          <div class="field-body">
            <div class="field is-expanded">
              <div class="field has-addons">
                <p class="control">
                  <a class="button is-static">
                    +44
                  </a>
                </p>
                <p class="control is-expanded">
                  <input class="input" type="tel" placeholder="Your phone number">
                </p>
              </div>
              <p class="help">Do not enter the first zero</p>
            </div>
          </div>
        </div>
        <div class="field is-horizontal">3
          <div class="field-label is-normal">
            <label class="label">Department</label>
          </div>
          <div class="field-body">
            <div class="field is-narrow">
              <div class="control">
                <div class="select is-fullwidth">
                  <select>
                    <option>Business development</option>
                    <option>Marketing</option>
                    <option>Sales</option>
                  </select>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="field is-horizontal">4
          <div class="field-label">
            <label class="label">Already a member?</label>
          </div>
          <div class="field-body">
            <div class="field is-narrow">
              <div class="control">
                <label class="radio">
                  <input type="radio" name="member">
                  Yes
                </label>
                <label class="radio">
                  <input type="radio" name="member">
                  No
                </label>
              </div>
            </div>
          </div>
        </div>
        <div class="field is-horizontal">5
          <div class="field-label is-normal">
            <label class="label">Subject</label>
          </div>
          <div class="field-body">
            <div class="field">
              <div class="control">
                <input class="input is-danger" type="text" placeholder="e.g. Partnership opportunity">
              </div>
              <p class="help is-danger">
                This field is required
              </p>
            </div>
          </div>
        </div>
        <div class="field is-horizontal">6
          <div class="field-label is-normal">
            <label class="label">Question</label>
          </div>
          <div class="field-body">
            <div class="field">
              <div class="control">
                <textarea class="textarea" placeholder="Explain how we can help you"></textarea>
              </div>
            </div>
          </div>
        </div>
        <div class="field is-horizontal">7
          <div class="field-label">
            <!-- Left empty for spacing -->
          </div>
          <div class="field-body">
            <div class="field">
              <div class="control">
                <button class="button is-primary">
                  Send message
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
