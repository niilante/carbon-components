### HTML

The basic empty Footer has been removed.
Now there's only one variant of HTML for Footer that more closely resembles what's being used in Bluemix configuration pages.

### SCSS

The `_footer.scss` file is now located at __src/components/footer/_footer.scss__. You will need to update any `@import` statements for this file to reflect this change.

```scss
@import 'path_to_node_modules/@console/bluemix-components/src/components/footer/footer';
```

| Old Class                             | New Class                | Note      |
|---------------------------------------|--------------------------|-----------|
| bx--footer                            | bx--footer               | Unchanged |
|                                       | bx--footer--bottom-fixed | Added     |
|                                       | bx--footer-info          | Added     |
|                                       | bx--footer-info__item    | Added     |
|                                       | bx--footer-info__label   | Added     |
|                                       | bx--footer-cta           | Added     |
| bx--footer__container                 |                          | Removed   |
| bx--footer--config                    |                          | Removed   |
| bx--footer--config__container         |                          | Removed   |
| bx--footer--config__information       |                          | Removed   |
| bx--footer--config__support           |                          | Removed   |
| bx--footer--config__support-question  |                          | Removed   |
| bx--footer--config__submit            |                          | Removed   |
| bx--footer--config__submit-price      |                          | Removed   |
| bx--footer--config__settings-question |                          | Removed   |
