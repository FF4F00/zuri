## 💻 How to install via

- Install the latest version of <a href="https://deno.land/#installation"> Deno</a>.
- Install via 

```
deno install --allow-net --allow-read --allow-write --unstable https://deno.land/x/via/cli.ts
```
<details><summary>About Permissions</summary>
<ul>
  <li>--allow-net: Required for the dev server. </li>
  <li> --allow-read: Allows via to compile svelte files.</li>
  <li> --allow-write: Allows via to write to files it creates during the <code>via build</code> process</li>
  <li> --unstable: Allows the use of Deno's standard modules which might not be stable yet.</li>
</ul>
Read more about <a href="https://deno.land/manual@v1.16.2/getting_started/permissions">permissions</a> or <a href="https://deno.land/manual/runtime/stability">stability</a> here
</details>

## 💫  Overview
- After installing, run the following commands to get started.

```
via create my-app
cd my-app
via build
via dev
```
- After running <code>via dev</code>, open <a href=http://localhost:3000>http://localhost:3000</a> to see your app.</p>
- Make changes to the .svelte files in the source folder for live reloading on the browser.</p>



## ⭐ How to use via

- To create a project, type: 

```
via create [project name]
```
- To compile, first change directories to the root of the project (<code>cd [project name]</code>) then type:

```
via build
```

- To start developing, type: 

```
via dev
```

- This will start up the development server and will open a websocket listening for any changes to the <code>./src</code> folder. Upon saving changes, your svelte code will be compiled again and the browser will reload to reflect the changes.

## ✨ Features 


<ul>
  <li>Compiler</li>
  <li>Bundler</li>
  <li>Live Reloading</li>
</ul>
