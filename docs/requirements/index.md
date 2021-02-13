# Primary

- Photographer
  - Project
    - Create/update/remove projects
  - Gallery
    - Add and remove high-res images intuitively to/from project gallery
    - Select order of images in project gallery
    - Prevent full screen images from client page view
    - Display generated watermark images on client page view
      - By uploading an image and setting positions
    - Preview generated watermark example
    - Un/limit amount of media for package selection
  - Packaging
    - Add and remove images from package
    - Publish a new package. notify client
    - Must send a notification when package is downloaded
    - Must show in UI when package is downloaded
    - Must be able to package client chosen photos
  - Public client page
    - Un/publish client page, notify client
    - Protect client page by PIN
- Client
  - Must be able to see image gallery
  - Project page must be mobile/desktop friendly, images must load quickly
  - Must be able to request/select images for package, notify photographer on submit
  - Must be able to download package (when allowed)
  - Must be able restore selected packaged images from previous visit
  - Must be able to filter by selected, unselected, latest packaged
  - Must be able to get UI or process help
  - Must be able to view package via email

# User Stories

## Photographer

- As a photographer, I want to create a project
- As a photographer, I want to upload images to a project
- As a photographer, I want to remove selected images from a project
- As a photographer, I want to re-arrange the order of uploaded photos
- As a photographer, I want to watermark uploaded photos
- As a photographer, I want to upload a watermark
- As a photographer, I want to select positions of watermark
- As a photographer, I want to a preview watermark example image
- As a photographer, I want to disable full size images on client page
- As a photographer, I want to set a limit to package selection
- As a photographer, I want to set package selection to unlimited
- As a photographer, I want to add images to a package
- As a photographer, I want to remove images from a package
- As a photographer, I want to publish a new package
- As a photographer, I want to see if the package has been downloaded and when
- As a photographer, I want to create the package from requested photos
- As a photographer, I want to publish the client page
- As a photographer, I want to unpublish the client page

## Client

- As a client, I want to see a gallery of photos
- As a client, I want to see full screen photos
- As a client, I want to add photos to a package
- As a client, I want to remove a photo from a package
- As a client, I want to see selected photos only
- As a client, I want to see package photos
- As a client, I want to be notified when the package is published
- As a client, I want to be notified when the client page is published
- As a client, I want to get client page help

# Concepts

- Project: Acts as a unit/namespace for an individual photographer/client job
- Package: A collection of final images, acts as a deliverable for a client
- Client Page: A page a client can access to manage their package

# Guide

## Packaging

- Publishing the package will generate selected photos into a bundle, which is available for download for the client

# Secondary

- Photographer
  - Customise client page
  - Archive/unarchive project
  - Add video to packages

