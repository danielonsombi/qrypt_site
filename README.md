# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


Interesting Tips:
<!-- Accent -->
<div class="my-4 flex-col text-white ml-2">
    <label> <input type="checkbox" checked /> Browser default </label>
    <label> <input type="checkbox" class="accent-pink-500" checked /> Browser default </label> -> Changes the color of the checkbox
</div>

<!-- Fluid Texts.  Changes the text size with screensize. One doesn't have to use the media queries. -->
<p class="text-[min(10vw, 70px)]"> Something Fluid </p>

<!-- File-->
Tailwind has a way to manage files upload styling using the file prefix:
<label class="my-4 block">
    <input type="file" class="block w-full text-sm text-slate-500 file:mr-4 file:rounded-full file:border-0 file:bg-violet-50 file:px-4 file:py-2 file:text-sm file:font-semibold file:text-violet-700 hover:file:bg-violet-100" />
</label>


<!-- Highlight-->
<div class="selection:bg-green-400 selection:text-white">
    <p>Here you can find all the components available in the library. We are working on adding more components.</p>
</div>
