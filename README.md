# empty-component-destroy-repro

Repro for https://github.com/sveltejs/svelte/issues/7488.

`npm run build` then `npm start`. Visit [localhost:8080](http://localhost:8080) and observe that the `<Empty>` component's destroy callbacks do not run.

Demo: https://empty-component-destroy-repro.vercel.app/
