![Thumbnail](./src/thumbnail.svg)

<p align=center>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=figma,nextjs,astro,react,typescript,nodejs,express,js,css,sass,tailwind,html,prisma,postgresql,supabase,planetscale,vite,vitest,jest,cypress,md,cloudflare,vercel,netlify,vscode,github,codepen,pnpm,bun,npm,postman,notion,apple,windows,linux" />
  </a>
</p>

```jsx
// bun add @nattui/react-components
// bun add @nattui/tailwind-colors
// bun add @nattui/tailwind-exact

// global.css
@import "tailwindcss";
@import "@nattui/tailwind-colors";
@import "@nattui/tailwind-exact";

// component.tsx
import { Button, Input, Label } from "@nattui/react-components"

<Label className="mb-2" htmlFor="email">
  Email
</Label>
<Input
  autoComplete="email"
  className="mb-16"
  id="email"
  isRequired
  name="email"
  type="email"
/>
<Button type="submit">
  Sign in
</Button>
```

- [config-and-setup-notes](https://github.com/nattui/config-and-setup-notes)
