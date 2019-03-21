# BC Stencil HB Snips

Find particular value in an array:

```
{{#each product.custom_fields}}
    {{#if name '===' 'FINISH'}}
    <h1>It's there</h1>
          {{else}}
    <h1>It's not there</h1>
    {{/if}}
{{/each}}
```
