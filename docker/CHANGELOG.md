# Changelog

All notable changes to the fyne-cross docker images will be documented in this file.

Release cycle won't follow the fyne-cross one, so the images will be tagged using the label
year.month.day along with the latest one.

# Release 20.06.07
- Base image is based on dockercore/golang-cross@1.13.12 (Go v1.13.12)
- fyne cli updated to v1.3.0

# Release 20.05.21
- Base image is based on dockercore/golang-cross@1.13.11 (Go v1.13.11)
- Android image: upgrade fyne cli tool to develop to allow build for app fyne
  develop branch

# Release 20.05.10
- Add support for FreeBSD: lucor/fyne-cross:freebsd-latest

# Release 20.05.03
- Introduce new label versioning
- Base image is based on dockercore/golang-cross@1.13.10 (Go v1.13.10)
- Add dedicated images for linux 386, arm and arm64 #25
