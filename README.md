# Trainr

Trainr, part of Teachr Suite (Trainr, Learnr, Teamr, Graspr, Skillr) is an open source online training platform that is capable to run sites similar to Khanacademy. It is written in AngularJS with REST API for high performance in mind.

> This is project is part of Agriya Open Source efforts. Trainr was originally a paid script and was selling around 12000 Euros. It is now released under dual license (OSL 3.0 & Commercial) for open source community benefits.

![trainr_banner](https://user-images.githubusercontent.com/4700341/47853825-02074100-de06-11e8-9c92-7a3d38c7b9cf.png)

## Support

Trainr is an open source online training project. Full commercial support (commercial license, customization, training, etc) are available through [Trainr platform support](https://www.agriya.com/products/udemy-clone)

Theming partner [CSSilize for design and HTML conversions](http://cssilize.com/)

## Teachr Suite

Agriya Teachr Suite is a open source online training platform that caters to Trainr, Learnr, Teamr, Graspr, Skillr.

* Trainr - trainr online training like or similar to Khanacademy.

* Learnr - learnr flourishing e-learning business model like Udacity.

* Teamr - teamr online training marketplace like or simiar to treehous.

* Skillr - skillr online learning concept like or similar to Skillshare.

* Graspr - graspr is highly capable of rendering learning platform like or similar to Coursera.

## Features

### Social Logins

This feature is enabled to make the sign-up process simple for the users with the social media logins with Facebook, Twitter and Google+.
  
### Course Search

Users can search based on the filters like price, course language, category and instructional levels.

### SocialShare

In course page there is way to share and promote the courses through social media site like Facebook, Google+ and Twitter.

### Instructor Dashboard

Every instructor gets a dedicated dashboard in which they can find the number of students enrolled in the course and much more. The instructor can manage their all courses from here.

### Learner Dashboard

It has users learning and wishlist courses. We display the course progress bar and provide course rate options here. Also it has some course filters too. 

### Online Lessons

* ArticleLessons: Instructor can add article type lessons.
* DownloadableFileLessons: Instructor can add downloadable type lessons for giving practice and exercise files, exe files and etc to learners.
* VideoLessons: Instructor can add video lessons into their courses.
* VideoExternalEmbedLessons: Instructor can add video lesson of external sites like from YouTube, Vimeo etc (using embed code).

### Preview

Instructor can post preview lesson for encourage the learners to book the course.

### Promo Video

Instructor can add sort promo video for their course to encourage the learners to book the course.

### Withdrawal

Instructor can withdraw their revenue amount

## Getting Started

### Prerequisites

#### For deployment

* PostgreSQL
* PHP >= 5.5.9 with OpenSSL, PDO, Mbstring and cURL extensions
* Nginx (preferred) or Apache

#### For building (build tools)

* Nodejs
* Composer
* Bower
* Grunt

### Setup

* PHP dependencies are handled through `composer` (Refer `/server/php/Slim/`)
* JavaScript dependencies are handled through `bower` (Refer `/client/`)
* Needs writable permission for `/tmp/` and `/media/` folders found within project path
* Build tasks are handled through `grunt`
* Database schema 'sql/course_with_empty_data.sql'

### Contributing

Our approach is similar to Magento. If anything is not clear, please [contact us](https://www.agriya.com/contact).

All Submissions you make to Trainr through GitHub are subject to the following terms and conditions:

* You grant Agriya a perpetual, worldwide, non-exclusive, no charge, royalty free, irrevocable license under your applicable copyrights and patents to reproduce, prepare derivative works of, display, publicly perform, sublicense and distribute any feedback, ideas, code, or other information ("Submission") you submit through GitHub.
* Your Submission is an original work of authorship and you are the owner or are legally entitled to grant the license stated above.


### License

Copyright (c) 2014-2018 [Agriya](https://www.agriya.com/).

Dual License (OSL 3.0 & [Commercial License](https://www.agriya.com/contact))
