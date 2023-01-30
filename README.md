# Exercise - Spring Boot - Swagger 1
* write a Spring Boot application that uses the following dependencies:
  * `Lombok`
  * `Spring Boot DevTools`
  * `Spring Web`
* add just 1 necessary dependency to the `pom.xml` for `springfox`:
  * `springfox-boot-starter`
* in `application.yml` add the following configuration:
  * `spring.mvc.pathmatch.matching-strategy=ant_path_matcher`
    * remember to [convert](http://mageddo.com/tools/yaml-converter) from `properties` to `yaml`
* expose the swagger with some `ApiInfo` and 1 random `Tag` regarding the `name-controller` that returns your name
* run the Spring application on port `1234`
* provide a default controller for the root with a welcome message (e.g. for someone who visit `localhost:1234`)
