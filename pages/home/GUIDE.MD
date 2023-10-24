
# Starter Pack between CSS and Tailwind

!!-Usar leitor de MarkDown-!!
==================

## Sumário
- [Padding](#padding)

- [Margin](#margin)

- [Display](#display)

- [Exemplos](#exemplos-na-prática)

[Documentação oficial do Tailwind](https://tailwindcss.com/docs)

---

> ## Padding ([Docs](https://tailwindcss.com/docs/padding))
>  
> - CSS
> 
> ```css
> div {
>   padding: 20px;
> }
> ```
> 
> ---
> 
> - Tailwind
> 
> ```HTML
> <div class="p-4">s
>   foo
> </div>
> ```

---

> ## Margin ([Docs](https://tailwindcss.com/docs/margin))
>  
> - CSS
> 
> ```css
> div {
>   margin: 20px;
> }
> ```
> 
> ---
> 
> - Tailwind
> 
> ```HTML
> <div class="m-4">
>   bar
> </div>
> ```

---

> ## Display ([Docs](https://tailwindcss.com/docs/display))
>  
> - CSS
>
> ```css
> div {
>   display: flex;
>   flex-direction: column;
> }
> ```
> 
> ---
> 
> - Tailwind
> 
> ```HTML
> <div class="flex flex-col">
>   bar
> </div>
> ```

---

## Exemplos na prática

> Pegando esse header na prática:
> ```HTML
> <header>
>     <span class="material-symbols-outlined"id="menu">
>         menu
>     </span>
>     <h1>
>         <span>Rodrigo</span>
>         <span>Car</span>
>     </h1>
> </header>
> ```
>
> ---
>
> <table>
> <tr>
> <td> CSS </td>
> <td> Tailwind </td>
> </tr>
> 
> <tr>
> <td>
> 
> ```CSS
>   header {
>     width: 100%;
>     display: flex;
>     align-items: center;
>     padding: 20px 10px;
>     justify-content: space-between;
>
>     background-color: var(--black);
>     color: var(--white);
>   }
> ```
>
> </td>
> <td>
> 
> ```HTML
>   <header class="
>        w-full
>        flex 
>        align-center 
>        px-2 
>        py-4 
>        justify-between 
>        bg-black
>        text-white
>    ">
>     bar
>    </header>
> ```
> 
> </td>
> </tr>
> <tr>
> </tr>
> </table>