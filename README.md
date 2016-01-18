# docker-wkhtmltopdf
This docker container lets you run wkhtmltopdf in a docker container.

## Building the image

```sh
docker build .
```

## Using the image

```sh
docker run -v <host_dir>:<container_dir> openlabs/docker-wkhtmltopdf http://www.google.com <container_dir>/output.pdf
```

The mounted volume can be used to send local html files and to save the output.

## Bugs and questions

The development of the container takes place on [Github](https://github.com/taktsoft/docker-wkhtmltopdf). If you have a
question or a bug report to file, you can report as a github issue.
