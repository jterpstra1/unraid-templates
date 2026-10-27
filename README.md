# unraid-templates
this repo will contain all my unraid templates

## docker-s3sync
[docker-s3sync.xml](docker-s3sync.xml)
Based on the already available s3sync CA App. This version however has been updated and now contains AWS CLI V2 and no longer requires the previously included python packages. The image is published to `ghcr.io/jterpstra1/docker-s3sync` for amd64 and arm64.

## tapo-rest-sc
[tapo-rest-sc.xml](tapo-rest-sc.xml)
A lightweight REST API for fetching power data from Tapo smart devices, packaged for Docker deployment.

## grimmory-convert
[grimmory-convert.xml](grimmory-convert.xml)
Converts books in a Grimmory library to extra formats (e.g. EPUB to AZW3) with Calibre and saves them next to the original, so Grimmory picks them up as extra formats of the same book.

## ebook-convert-sidecar
[ebook-convert-sidecar.xml](ebook-convert-sidecar.xml)
Converts the books in your library folder to extra formats (e.g. EPUB to AZW3) with Calibre and saves them next to the original. Works with library apps that treat same-named files in one folder as one book, such as Grimmory and BookOrbit.
