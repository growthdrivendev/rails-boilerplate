# The Rails boilerplate by Growth Driven Development

This boilerplate was created to speed up the process of learning how to create a Ruby on Rails apps during the courses posted on the [http://gddev.org](http://gddev.org) education platform.

## Project configuration

The only thing you have to do before start working with this boilerplate is to change the application name. In order to do this, you can use the `./configure.sh` shell script which accepts the new application name as the argument. So, if your application should be named `Guestbook` then call the shell script this way:

```
./configure.sh Guestbook
```

it will update the `config/application.rb` file and the application layout.

## Stack

The project comes with the newest stable version of the Ruby language and the Ruby on Rails framework.

* Ruby `2.5.0`
* Rails `5.2.0`

Following gems are already bundled in the project:

* **Pry** - [https://github.com/pry/pry](https://github.com/pry/pry) - alternative development console and great debugging tool
* **HAML** - [https://github.com/indirect/haml-rails](https://github.com/indirect/haml-rails) - templating engine for HTML to make it easier to write the code
