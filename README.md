# README

## Design Template

https://www.figma.com/file/12uOREA4rkJrXGELg9gKgk/Portfolio---Design-Template-1

## Anti-bot mailto

from <https://css-tricks.com/how-to-safely-share-your-email-address-on-a-website/>

```html
<form
  action="javascript:location.href=('mail' + 'to' + ':test' + '@domain.com')"
>
  <button>Email me</button>
</form>
```
