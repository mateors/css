# Tailwindcss

## Get started
Download the tailwindcss standalone-cli from https://github.com/tailwindlabs/tailwindcss/releases/tag/v3.1.8
windows user download from [here](https://github.com/tailwindlabs/tailwindcss/releases/download/v3.1.8/tailwindcss-windows-x64.exe).
After download rename it to `tailwindcss` (because everytime you use this to interact with your terminal)


## Step-1 Create a tailwind.config.js file
`./tailwindcss init`

> `./tailwindcss init tailwindcss-config.js` custom config file

## Step-2 Start a watcher
`./tailwindcss -i input.css -o output.css --watch`

## Step-3 Compile and minify your CSS for production
`./tailwindcss -i input.css -o output.css --minify`


> To use first-party plugins (directly from tailwindcss)

just require them in your `tailwind.config.js` file like you would in a Node-based project:

```js
module.exports = {
  // ...
  plugins: [
    require('@tailwindcss/forms'),
    require('@tailwindcss/typography'),
  ]
}
```


1. Tooltip
2. Popover
3. custom dropdown
4. Navbar
5. Layout
6. CSS sprites

 
### to create your tailwind-config file use the following command
> `./tailwindcss.exe init`

Above command will give you the following message if your tailwind-config-js file is alreay exist

> tailwind.config.js already exists.

When you use a custom file name, you will need to specify it as a command-line argument when compiling your CSS with the Tailwind CLI tool:
```
tailwindcss -c ./tailwindcss-config.js -i input.css -o output.css
```

> scaffold a complete configuration file that includes all of Tailwind’s default configuration, use the --full option:
```
tailwindcss init --full
```


## Resource
* [Tailwind CSS Bangla Tutorial Series](https://www.youtube.com/playlist?list=PLHiZ4m8vCp9P23SqlHL0QAqiwS_oCofV2)
* [Standalone-cli guide](https://tailwindcss.com/blog/standalone-cli)
* [Download standalone-cli](https://github.com/tailwindlabs/tailwindcss/releases/tag/v3.1.8)
* [Tailwind Crash Course | Project From Scratch](https://www.youtube.com/watch?v=dFgzHOX84xQ)
* [Build a Modern Landing Page With Tailwind CSS](https://www.youtube.com/watch?v=00gyCtIQp8E)
* [The Net Ninja|Tailwind CSS Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gpXORlEHjc5bgnIi5HEGhw)
* [Tailwind Just in Time Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9ht1OMQPhBVKAb2dVLhg-MJ)
* [Styling Forms with Tailwind CSS](https://www.youtube.com/watch?v=pONeWAzDsQg)
* [Build & Deploy a Personal Portfolio with TailwindCSS](https://www.youtube.com/watch?v=Vp6GC3jKG20)
* [Floating Labels with Tailwind CSS](https://www.youtube.com/watch?v=nJzKi6oIvBA)
* [Translating a Custom Design System to Tailwind CSS](https://www.youtube.com/watch?v=cZc4Jn5nK3k)
* [What’s new in Tailwind CSS?](https://www.youtube.com/playlist?list=PL5f_mz_zU5eV0_7udNKr3qffGCkJ4Avb_)
