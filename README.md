# Mexpro Jekyll

Mexpro's site reimplemented using [Jekyll](https://jekyllrb.com/).

## Getting Started

For development on this site, use Docker and Jekyll's development server.
Docker reduces the effort required to get the development server up and
running, while Jekyll's development server makes viewing your changes painless.
To get started,
[install Docker](https://docs.docker.com/engine/installation/)
(and docker-compose).  Then use the handy-dandy `aliases` file in the root
of the project to get some shortcut commands:

    $ source ./aliases

Now, to start the development server, use the `start` alias.  To stop
the server, use ctrl+c.  To clean up after the server, use `stop`.

    $ start
    Building web
    Step 1 : FROM exegete46/jekyll:onbuild
    <snip>
    web_1 |   Server running... press ctrl-c to stop.
    <ctrl+c>
    $ stop
    Stopping mexpro_web_1 ... done
    Removing mexpro_web_1 ... done
    Removing image mexpro_web

## About Jekyll

Jekyll is a tool used for building websites that are focussed on speed of
development and overall speed of the site.  The output of Jekyll's `build`
command is a static HTML site, however designers to use advanced tools such as
[SASS](http://sass-lang.com/)
and
[Markdown](https://daringfireball.net/projects/markdown/),
as well as features like layouts and includes,
to create consistent pages without minimal effort.
## Learn More

To learn more, check out the
[Jekyll Documentation](https://jekyllrb.com/docs/home/).
The Docker image has access to all of the commands you can use in Jekyll,
for reference read about the
[Jekyll Docker Image](https://github.com/exegete46/docker-jekyll/).
