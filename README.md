Svelte CodeMirror component
---------------------------

Provides an abstraction layer over CodeMirror that reduces the setup needed to make it work with Svelte.

## Demo

https://svelte.dev/repl/b2c657e8c49a42b6ba6aaf3dbd7d09d5

## Install 
npm i @joshnuss/svelte-codemirror

or 

npm i git+https://github.com/hunkim/svelte-codemirror.git


## Usage

```html
<script>
  import 'codemirror/lib/codemirror.js' // codemirror
  import 'codemirror/mode/python/python' // python mode
  import CodeMirror from '@joshnuss/svelte-codemirror'
  
  let editor = null
</script>

<CodeMirror bind:editor options={{ lineNumbers: true, mode: "javascript"}} value='def f(a):'/>
```

## License

MIT
