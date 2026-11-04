# Portfolio guide

## Add a project
Create a file in `_projects/`, copy the front matter from an existing one, and set `order`. Set `featured: true` to show it on the home page. Projects are grouped on /projects/ by the `product` value.

## Add an image or GIF
Put the file in `assets/images/` and add this to a page:

    {% include figure.html src="/assets/images/your-file.png" alt="What the image shows" caption="Optional caption" %}

Always write alt text. For video, upload an MP4 to `assets/images/` and use an HTML `<video controls>` element with a `<track>` for captions.

## Change navigation
Edit `_data/navigation.yml`. The resume link comes from `resume:` in `_config.yml`.

## Change colors
Edit the variables at the top of `assets/css/style.scss`.

## Placeholders
Text inside `<!-- ... -->` comments is a prompt for content to add. It does not publish.
