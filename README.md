# ld_svelte

A simple example of switching the page's background color based on a flag's value from LaunchDarkly. 
The example uses LaunchDarkly's svelte SDK

## To Run
* Edit __src/App.svelte__ such that:
    * Add Client SDK key
    * Change flag key to suit your environment 
        * NOTE: The flag should be type:string as the background color is passed as value 
* Follow [svelte setup instructions](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Svelte_getting_started) to complete setup

Vite.JS for frontend tooling -- frankly, overkill for this effort 