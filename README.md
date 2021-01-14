# GR0 Front-End Developer Coding Test
Thanks for participating in the GR0 Front-End Developer Coding Test! This test is broken down into two assignments, one for General Development tasks, and the other for Wordpress- and SEO-specific tasks. The total time requirement estimated for these tasks is 2 hours.

## Requirements
In order to complete this task, you will need access to Docker, including the `docker-compose` command.

## Getting Started
Fork this repository, clone your fork, and navigate to the project's root directory using your terminal emulator of choice. The tasks can be completed in any order you wish; see the relevant sections below for instructions to get started on each task.

### General Development
Open your browser of choice and navigate to the page at `$PROJECT_ROOT_DIR/general/index.html`. The instructions for the General Development assignment are detailed on that page.

### Wordpress
Navigate to the `wp/` subdirectory and run the following command:

```shell
docker-compose up -d
```

This will start the Docker container in the background. Once everything is up-and-running, open your browser of choice and navigate to `http://localhost:8000/` and install Wordpress on the site.

Once Wordpress has successfully been installed, install and activate the [All-In-One WP Migration plugin](https://wordpress.org/plugins/all-in-one-wp-migration/) and import the site that is located in `wp/assets/archive.wpress`.

When the migration completes, open a new tab to `http://localhost:8000/` to see the instructions for the Wordpress assignment.

> After you have completed the Wordpress assignment, use the All-In-One WP Migration plugin to export the site and save the file at `wp/results.wpress`.

## Submission
Once you have completed both assignments, push your local changes back to your fork of the repository, and respond to your GR0 contact with a link to the repository. We'll be in touch.