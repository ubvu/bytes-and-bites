# Website for Bytes-and-Bites

## License notes

Please note that the CC license attached to this project applies only to the qmd files for the website. Notebooks, presentations, and linked images are property of the owner and you must follow their own licensing. For those wanting to use the images created for Bytes & Bites then please provide credit and direct to the website, other than that you are free to use them as you wish!

## How to contribute

Besides cloning this respository, you need to install [quarto](https://quarto.org/docs/get-started/).

[Here](https://quarto.org/docs/websites/) you find the documentation on building websites.

To see changes locally, run the preview command:

```bash
$ quarto preview
```

Before committing, render once more so that redundant files are not pushed to the repository.

```bash
$ quarto render
```

Stage and commit your changes, then push to this repository.
The website is automatically refreshed by github actions.

## How to add content

### Events

The folder */events* contains .qmd files (one per event) with simple markup. Check out existing event files to get an idea about how to add new ones. Added events will appear on the events page.
