Protection Profile Template


Protection Profile or Extended Package for Certification Authorities
===============

![Build](https://github.com/commoncriteria/certauth/workflows/Build/badge.svg)
[![GitHub issues Open](https://img.shields.io/github/issues/commoncriteria/certauth.svg?maxAge=2592000)](https://github.com/commoncriteria/certauth/issues) 
![license](https://img.shields.io/badge/license-Unlicensed-blue.svg)

## Draft Version

* [Protection Profile for Certification Authorities](https://commoncriteria.github.io/certauth/master/certauth-release.html) (html)
* [Protection Profile for Certification Authorities](https://commoncriteria.github.io/certauth/master/certauth-release.pdf) (pdf)

## Release Version
* [Protection Profile for Certification Authorities](https://www.niap-ccevs.org/Profile/Info.cfm?PPID=420&id=420)

## Contributing

If you are interested in contributing directly to future versions the this Protection Profile, please consider joining the NIAP technical community.
* [How to join the NIAP Technical Community (Mailing list and updates)](https://www.niap-ccevs.org/NIAP_Evolution/tech_communities.cfm)

## Feedback

Questions, comments, and fixes can be submitted to the [repository issue tracker](https://github.com/commoncriteria/certauth/issues)

## Quickstart
To clone this project along with its _transforms_ submodule run:

````
  git clone --recursive git@github.com:commoncriteria/certauth.git
````
To pull updates from the upstream _transforms_ submodule and commit them run:
````
 git submodule update --remote transforms
 git add transforms
 git commit
````

### Development Info
[Help working with Transforms Submodule](https://github.com/commoncriteria/transforms/wiki/Working-with-Transforms-as-a-Submodule)

## Repository Content
* input - Contains the 'meat' of the project. It's the input content (in XML form) that gets transformed to readable html.
* output - The output directory where the html is placed after transformation.
* output/images - The directory where images are stored
* transforms - Points to the transform subproject which is really a repository for resources shared amongst many Common Criteria projects. You shouldn't need to modify it.

## Links 
* [National Information Assurance Partnership (NIAP)](https://www.niap-ccevs.org/)
* [Common Criteria Portal](https://www.commoncriteriaportal.org/)

## License
See [License](./LICENSE)
