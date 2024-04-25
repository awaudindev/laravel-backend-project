<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<!--
*** Thanks for checking out my repository. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<br />
<div align="center">
  <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  <h3>Laravel Starter Project</h3>
  <p>A journey to improve Laravel development</p>
</div>

## About The Project

This project is a data processing part of integration between mobile apps and nuxt.js pwa.

Here are the link to mobile apps and nuxt.js pwa repository:
* [![Nuxt][Nuxt-repo]][Nuxt-url]
* [![Flutter][Flutter-repo]][Flutter-url]

## Getting Started

Setup [PostgreSQL](https://www.prisma.io/dataguide/postgresql/setting-up-a-local-postgresql-database) on your local environment.

Copy the .env.example and rename it .env, Update your .env configuration file.

```bash
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5433
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

Dont forget to run composer.

```bash
composer Install
```

Generate the app key

```bash
php artisan key:generate
```

Running the laravel

```bash
php artisan serve
```


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

please see [CONTRIBUTING.md](CONTRIBUTING.md) for more information.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Why Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/awaudindev/nuxt-starter-template.svg?style=for-the-badge
[contributors-url]: https://github.com/awaudindev/nuxt-starter-template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/awaudindev/nuxt-starter-template.svg?style=for-the-badge
[forks-url]: https://github.com/awaudindev/nuxt-starter-template/network/members
[stars-shield]: https://img.shields.io/github/stars/awaudindev/nuxt-starter-template.svg?style=for-the-badge
[stars-url]: https://github.com/awaudindev/nuxt-starter-template/stargazers
[issues-shield]: https://img.shields.io/github/issues/awaudindev/nuxt-starter-template.svg?style=for-the-badge
[issues-url]: https://github.com/awaudindev/nuxt-starter-templatee/issues
[license-shield]: https://img.shields.io/github/license/awaudindev/nuxt-starter-template.svg?style=for-the-badge
[license-url]: https://github.com/awaudindev/nuxt-starter-template/blob/master/LICENSE.txt
[Nuxt-repo]: https://img.shields.io/badge/Nuxt-00DC82?style=for-the-badge&logo=nuxt.js&logoColor=white
[Nuxt-url]: https://github.com/awaudindev/nuxt-starter-template
[Flutter-repo]:  https://img.shields.io/badge/Flutter-0468d7?style=for-the-badge&logo=flutter&logoColor=white
[Flutter-url]: https://github.com/awaudindev/Flutter-Simple-Project