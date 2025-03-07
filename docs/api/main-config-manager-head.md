---
title: 'managerHead'
---

Parent: [main.js|ts configuration](./main-config.md)

Type: `(head: string) => string`

Programmatically adjust the manager's `<head>` of your Storybook. For example, load a custom font or add a script. Most often used by [addon authors](../addons/writing-presets.md#babel).

<div class="aside">

💡 If you don't need to programmatically adjust the manager head, you can add scripts and styles to `manager-head.html` instead.

</div>

For example, you can conditionally add scripts or styles, depending on the environment:

<!-- prettier-ignore-start -->

<CodeSnippets
  paths={[
    'common/main-config-manager-head.js.mdx',
    'common/main-config-manager-head.ts.mdx',
  ]}
/>

<!-- prettier-ignore-end -->
