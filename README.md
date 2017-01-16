<img src="https://upload.wikimedia.org/wikipedia/en/3/30/Java_programming_language_logo.svg" alt="Java Logo" height="50px"/>

#Treehouse Java Web Techdegree Resources


This is a community based list of resources for the [Java Techdegree](https://www.teamtreehouse.com). 

Want to help and add resources? Awesome! Checkout our [CONTRIBUTING guidelines](CONTRIBUTING.md). 
 
## Index

[Java](#java) · 
[Spring](#spring) · 
[Spark](#spark) · 
[HTML](#html) · 
[CSS](#css) · 
[JavaScript](#javascript) · 
[General](#general) · 
[Slack](#slack) · 
[Career](#career) · 
[Git and GitHub](#git-and-github)

 
-------
 
### Java

* **[Java Software - Oracle](https://www.oracle.com/java/index.html)**
* **[Java Design Patterns](https://github.com/iluwatar/java-design-patterns)**
* **[Java Practices](https://google.github.io/styleguide/javaguide.html)**

### Spark

* **[Spark Framework Main Page](http://sparkjava.com)**
* **[Link cookie constructor to be used](https://github.com/perwendel/spark/blob/master/src/main/java/spark/Response.java#L215)** - 
This link was shared like 5-10 times in Slack by
[Craig Dennis](https://github.com/craigsdennis). It simply points
to the cookie constructor with many arguments, in which we 
can provide `"/"` as first argument instead of default one `""`.
So shortly saying, in Project-4 we better set cookie with `"/"` path so that 
we can use cookie on all pages of the website. 
This way we can set our password cookie working on
many protected pages (by default cookie will be available for only one page).
* **[Link to awaitInitialization in Spark](http://sparkjava.com/documentation.html#awaitinit)** -
This link is important note for all those who want to write
Unit Tests with Spark Framework. Was given to me in Slack
by [Craig Dennis](https://github.com/craigsdennis). It has to
be put in `@BeforeClass` annotated method when trying to
test app like [Craig Dennis](https://github.com/craigsdennis) does
in [Build a REST API with Spark Workshop](https://teamtreehouse.com/library/build-a-rest-api-in-spark).
[Here](https://github.com/nikiforov-alexander/pt4-spark-blog/blob/master/src/test/java/com/teamtreehouse/blog/MainTest.java#L60)
can be found example of usage `awaitInitialization`.
And [here](https://teamtreehouse.com/community/rest-api-with-sparkjava-custom-apiclient) 
is a link to Treehouse Community with the error that 
you will get if you don't put `awaitInitialization`.

### Spring

* **[Spring Framework Main Page](https://spring.io)**
* **[Spring Data REST Documentation](http://docs.spring.io/spring-data/rest/docs/current/reference/html/)** -
Helpful documentation link especially in Techdegree Project-10
* **[Spring Data JPA Documentation](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)** -
Helpful documentation link for all courses with [Chris Ramacciotti](https://github.com/christherama), 
where he used `@Query`,
like [Deploying a Spring Application](https://teamtreehouse.com/library/deploying-a-spring-application),
[User Authentication in Spring](https://teamtreehouse.com/library/user-authentication-in-spring)
and [Spring Unit Testing](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
* **[Opinion about Field Injection in Spring](https://www.petrikainulainen.net/software-development/design/why-i-changed-my-mind-about-field-injection/)** -
Opinion about Field Injection in Spring Applications. Was provided by [Craig Dennis](https://github.com/craigsdennis)
after Project-10 discussion in Slack. It explains nice things about using `@Autowired`
in Spring. 


### HTML

* **[HTML Validation](https://validator.w3.org/)**

### CSS

* **[CSS Validation](https://jigsaw.w3.org/css-validator/)**

### JavaScript

* **[JS Hint](http://jshint.com/)** - A JavaScript validator

### General

* **[15 SEO Best Practices](https://moz.com/blog/15-seo-best-practices-for-structuring-urls)** - 
Best Practices for structuring URLs. The link was found by [Craig Dennis](https://github.com/craigsdennis)
some while ago.
It helps a lot in all web development Techdegree projects, in building URLs
and providing BackEnd for them. Although some of the practices can be 
hard to be implemented easily, it is still nice to know professional
opinion on this topic.

### Slack

* 

### Career

* 

### Git and GitHub

* **[Naming conventions for Git and GitHub repositories](http://stackoverflow.com/questions/11947587/is-there-a-naming-convention-for-git-repositories)** -
It was hard to find general article on official Git or GitHub websites
about this topic. So here is the StackOverflow post, that was also
approved by [Craig Dennis](https://github.com/craigsdennis) in Slack
discussions. It also relies indirectly to the question of whether
we should use capital letters in URLs, see 
[15 SEO Best Practices](https://moz.com/blog/15-seo-best-practices-for-structuring-urls).

* **[How to write commit messages in Git](http://chris.beams.io/posts/git-commit/)** -
Super nice instruction about how commit messages should be written.
It is important to read this
article as early as possible, and start applying
Git Commit Best Practices early on for all Techdegree Projects
