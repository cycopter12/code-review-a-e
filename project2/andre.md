# Code Review for Andre

## Project Repo

[here](https://fathomless-springs-28288.herokuapp.com/)

## Review

#### Project Purpose

Purpose of Andre's project is to create awareness of healthier snack alternatives available.
Users are able to view and make comments on the products listed to provide their views/recommendations.
Future use of the site includes snack purchase and subscription services.

#### Project Organization

#### Features

* Models
  * 3 models of users(admin), snacks and comments
* Cloudinary for picture upload in products
  * The use of multer as a middleware and cloudinary as an cloud image management service.

#### Areas of Success (Code, Organization)

* Organization of project
  * Codes are well organized, concerns were separated clearly via routes and controllers.
* CSS
  * Colorful page layout; products are neatly displayed.

#### Areas for Improvement (Code, Organization)

* Users vs admin authentication
  * to provide flexibility and prevent loss of data by giving admin rights to certain users only.
* view layout of comments in individual products
  * clearer display format to provide clarity on commenter and comments.
