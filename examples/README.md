# Action examples

See the [build-pdf.yml file](./build-pdf.yml) for a general example action workflow yaml.

You need to set your parameters inside it:

```yaml
env:
  SLA_FILENAME: your-scribus-filename.sla
  #TODO
```

Copy this into your repository's `.github/workflows/buiild-pdf.yml`, and voilà, your automatic Scribus PDF export should work!
