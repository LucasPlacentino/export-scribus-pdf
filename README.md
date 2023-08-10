# use [https://github.com/sla2pdf-team/sla2pdf](https://github.com/sla2pdf-team/sla2pdf) ?  

# Export Scribus PDF
A Github Action to export Scribus .sla files to PDF.  
Can be used to automatically create a Github release with the exported PDF file from a Scribus `.sla` file on push and/or pull-request.

## Inputs

| ID             | Description                                          | Examples                      | Required | Defaults          |
| -------------- | ---------------------------------------------------- | ----------------------------- | -------- | ----------------- |
| `sla-filename` | `.sla` file to export to PDF                         | `magazine.sla`                | ❗       | N/A               |
| `pdf-filename` | Filename of the exported PDF                         | `magazine-public-release.pdf` | &cross;  | TODO              |
|TODO|TODO|TODO|&cross;|TODO|
|...|...|...|...|...|

## Outputs

| ID             | Description                  | Default                                 |
| -------------- | ---------------------------- | --------------------------------------- |
| `pdf-file`     | Exported PDF file            | the name of your `.sla` file but `.pdf` |
|TODO|TODO|TODO|
|...|...|...|

## Examples
Check the [/examples directory](/examples) for example action yaml files.

```yaml
#TODO
```

-------------------

# Hello world docker action

This action prints "Hello World" to the log or "Hello" + the name of a person to greet. To learn how this action was built, see "[Creating a Docker container action](https://docs.github.com/en/actions/creating-actions/creating-a-docker-container-action)" in the GitHub Docs.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-docker-action@main
with:
  who-to-greet: 'Mona the Octocat'
```
