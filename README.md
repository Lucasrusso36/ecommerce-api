<p  align="center">Ecommerce</p>

<p  align="center">

<a  href="https://ruby-doc.org/core-2.7.1/">

<img  alt="Ruby Version"  src="https://img.shields.io/badge/Ruby-2.7.1 -green.svg"  target="_blank">

</a>

<a  href="https://guides.rubyonrails.org/6__release_notes.html">

<img  alt=""  src="https://img.shields.io/badge/Rails-~> 6.0.3.3-blue.svg"  target="_blank">

</a>
</p>


## Stack the Project

- **Ruby on Rails API**

- **React/Next**   

- **Postgresql**

- **Rspec(TDD)**


# Ecommerce

Development of api ecommerce of games using Ruby on Rails and FrontEnd using React/Next.

## Building application

Ok, so first you must have:

1. Postgresql installed.

2. Ruby >= 2.7.1 installed (minimum required for Rails 6.0.3.3, version we're working with).

3. As we're on the beginning of project, don't forget to right configure your `datatabe.yml`.

4. And to *bundle* it with command:

```
bundle install
```

### Manually building everything

If you want to rock and create your dev environment and data, it's possible to go through the usual way

1. Create databases
```
rails db:create
```

2. Run migrations
```
rails db:migrate
```

3. Start the server
```
rails s
```

If you want to run tests: 
```
bundle exec rspec
```
