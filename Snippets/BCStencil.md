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

Trigger particular CSS if custom settings are set:

```
{{#if theme_settings.uppercase}}
    <div class="uppercase">
{{else}}
    <div class="lowercase">
{{/if}}
```

Permissions based on customer groups:

```
{{#if customer.customer_group_id '==' '1'}}
    <li class="navUser-item cost-button" accesskey="a">
        <span>cost</span>
    </li>
{{/if}}
```
