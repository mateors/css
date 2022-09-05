# Tailwindcss

## Get started
Download the tailwindcss standalone-cli from https://github.com/tailwindlabs/tailwindcss/releases/tag/v3.1.8
windows user download from [here](https://github.com/tailwindlabs/tailwindcss/releases/download/v3.1.8/tailwindcss-windows-x64.exe)

after download rename it to tailwindcss (because everytime you use this to interact with your terminal)


## Step-1 Create a tailwind.config.js file
`./tailwindcss init`

## Step-2 Start a watcher
`./tailwindcss -i input.css -o output.css --watch`

## Step-3 Compile and minify your CSS for production
`./tailwindcss -i input.css -o output.css --minify`


> to use first-party plugins
just require them in your `tailwind.config.js` file like you would in a Node-based project:

```
module.exports = {
  // ...
  plugins: [
    require('@tailwindcss/forms'),
    require('@tailwindcss/typography'),
  ]
}
```

## Resource
* [Standalone-cli guide](https://tailwindcss.com/blog/standalone-cli)
* [Download standalone-cli](https://github.com/tailwindlabs/tailwindcss/releases/tag/v3.1.8)