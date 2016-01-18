# taktsoft/docker-wkhtmltopdf

This docker container lets you run wkhtmltopdf in a docker container.

## Building the image

```sh
docker build .
```

## Using the image

```sh
docker run -v <host_dir>:<container_dir> taktsoft/docker-wkhtmltopdf https://www.taktsoft.com <container_dir>/taktsoft.pdf
```

The mounted volume can be used to send local html files and to save the output.

## Bugs and questions

The development of the container takes place on [Github](https://github.com/taktsoft/docker-wkhtmltopdf). If you have a
question or a bug report to file, you can report as a github issue.


## Authors and Contributors

This image was built at [Taktsoft](https://www.taktsoft.com) and is based on
[openlabs/docker-wkhtmltopdf](https://github.com/openlabs/docker-wkhtmltopdf)
built at [Openlabs](http://www.openlabs.co.in).