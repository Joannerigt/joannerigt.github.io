# Joanne's Portfolio


## Installing

This project uses `Jekyll` site-generator to build the portfolio-site.
This means that Jekyll's installation instructions apply; see [here](https://jekyllrb.com/docs/installation/)

## Running

To run this project, run `bundle exec jekyll serve` in a terminal.
Alternatively, doubleclick `start_jekyll_on_windows.bat` if you're on windows.

If there's ever any errors, you know where to find me. You might try to just run `bundle install` in a terminal which will try to update application dependencies, but of course it very much depends on the error. Although I don't think there will be errors for the forseeable future. ;-)

## Editing


### Adding a 'skill'

Add a new list-item to the `/_data/skills.yml` file that contains the required fields.

The images for the skills are stored in `/images/skills/`.


### Adding a social media link/icon

Add a new list-item to the `/_data/social_media.yml` file that contains the required fields.

The images for the social media items are stored in `/images/social_media/`.
These images are expected to be in `.svg` or `.png` format (or some other format with transparency). 
They will be rendered as a square, so make sure the image aspect ratio is also square.

### Adding a Portfolio-item

Copy one of the existing files in `/portfolio/_posts/`.
The new file should have a name like `YYYY-MM-DD-some_file_name`. The date at front is only used to sort portfolio items (newer dates go at the top).
If you name a file without the date at the front, it will not show up in the portfolio list (this can be used to save 'draft' portfolio-items if you so desire).

The images for the skills are stored in `/portfolio/images/`.

### Changing something else

Most other settings (e-mail address, profile picture, site title) can be changed in `/_config.yml_`. Do note that after changing this file you'll need to restart Jekyll to see the changes.


Images not belonging anywhere else are stored in `/images/` directly.

## Publishing

By commiting + pushing the changes to the `master` branch in this repository, they will be published to GitHub pages, and visible at https://joannerigt.github.io/ .
