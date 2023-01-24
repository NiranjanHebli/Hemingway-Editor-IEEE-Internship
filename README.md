## Introduction 

The Hemingway App is an editor that highlights and corrects grammar, fluency, and sentence structure in order to help your writing read and look better. It’s a self-editing tool that allows you to write more concisely.

## Screenshot

![WhatsApp Image 2023-01-24 at 10 14 50 PM (1)](https://user-images.githubusercontent.com/84934990/214354983-2c7953f9-d57a-487f-9150-98bd51609864.jpeg)

## Get started

```bash
npm install
```

```bash
npm run dev
```

Navigate to [localhost:8080](http://localhost:8080). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.

If you're using [Visual Studio Code](https://code.visualstudio.com/) we recommend installing the official extension [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode). If you are using other editors you may need to install a plugin in order to get syntax highlighting and intellisense.

## Building and running in production mode

To create an optimised version of the app:

```bash
npm run build
```

You can run the newly built app with `npm run start`. This uses [sirv](https://github.com/lukeed/sirv), which is included in your package.json's `dependencies` so that the app will work when you deploy to platforms like [Heroku](https://heroku.com).


## Single-page app mode

By default, sirv will only respond to requests that match files in `public`. This is to maximise compatibility with static fileservers, allowing you to deploy your app anywhere.

If you're building a single-page app (SPA) with multiple routes, sirv needs to be able to respond to requests for *any* path. You can make it so by editing the `"start"` command in package.json:

```js
"start": "sirv public --single"
```


### With [Vercel](https://vercel.com)

Install `vercel` if you haven't already:

```bash
npm install -g vercel
```

Then, from within your project folder:

```bash
cd public
vercel deploy --name my-project
```

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:



npm run build
surge public my-project.surge.sh


# Contributors
[Niranjan Hebli](https://github.com/NiranjanHebli)                                     
[Yash Adake](https://github.com/YashAdake)                                                   
[Ann Mariya Roy](https://github.com/Ann-M-R)
[Gaurav Gupta](https://github.com/codinggaurav7)
