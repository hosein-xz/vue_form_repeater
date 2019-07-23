
<h1 align="center">Vue Form Repeater</h1>
<p align="center">
  <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/hosein-xz/vue_form_repeater.svg">
  <img alt="GitHub" src="https://img.shields.io/github/license/hosein-xz/vue_form_repeater.svg">
</p>

## Install

### NPM
Installing with npm is recommended and it simply works :<br><br>
```
npm i vue_form_repeater
```

### Download
You can download latest version from the Github: Download

## Quick start
To use in your project, just import `vue_form_repeater` and install into Vue.<br><br>
```
import vue_form_repeater from 'vue_form_repeater'

Vue.use(vue_form_repeater)
```

then you should just add any input you want in `slot`. For Example :<br><br>
```
<vue_form_repeater>
    <div class="col">
      <div class="form_group">
         <div class="form_label">
            <label class="label">Name</label>
         </div>
         <div class="form_control">
             <input type="text" nclass="form-control" >
         </div>
      </div>
    </div>
</vue_form_repeater>

```

## License
#### MIT
