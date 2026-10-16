<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Preserve the uploaded TanStack storefront routes and shared shop provider to retain the original menu, cart, delivery and checkout.
- Store imported photos as Lovable Assets JSON pointers so uploaded media stays outside the source bundle.
- Keep light and dark appearance in shared semantic CSS tokens and one header control so every page switches together.
- Validate and price guest orders in the server function; read TELEGRAM_BOT_TOKEN only inside its handler and never expose credentials or customer data in logs.
