# sisyphus.css

CSS components I'm tired of writing.

## Pseudo Element Setup

### `.ps, .ps--a, .ps--b`

```css
.ps{
  position:relative;
}

.ps:after,.ps:before{
  content:'';
  display:block;
  position:absolute;
}
```
