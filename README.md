![](https://toasty.is-pretty.cool/5wRB3Ux.gif)

## Pi Finder

Pi-Finder is a tool that allows you to get the index of a specific integer in the first million digits of Pi Number. The tool is a basic NodeJS Express application which allows you to get information with a single get request.
The path of the request is `/get/number` and the query number is the string that you want tool to find in Pi Number and return you with the index of that number. For an example, 
if you want to find `1415` on the tool, it would return index as **1** because the first digits of the Pi Number is `3,1415...`.

The visualized part is rendered as ejs which gives a better user experience. If you would like to host it locally you would need:

- NodeJS & NPM

If you have these packages, you are free to go. Open up a terminal or a Powershell Prompt and run `node app.js`. After running that, head over to `https://localhost:3000` on your browser
and here it is!