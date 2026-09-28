# Multi-brand tokens demo

A component library rebuilt from design tokens only. One set of components, switched at runtime by four attributes on `<html>`:

| Attribute | Values |
| --- | --- |
| `data-brand` | `brand-a` … `brand-g` |
| `data-theme` | `light`, `dark` |
| `data-density` | `default`, `compact`, `comfortable` |
| `data-shape` | `default`, `sharp`, `rounded` |

Brand names are anonymised. Brand G is an exploratory theme: red accent, neutral secondary and tertiary buttons, red links, warm greys, Hind with a 300/500 weight scale, and sharp corners by default.

Open the live page, or serve this folder locally:

```bash
python3 -m http.server 8000
```
