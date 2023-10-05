# 📚 Night Watch
A movie watchlist application that allows users to browse and bookmark movies to watch later.
<img width="1512" alt="Screen Shot 2023-09-20 at 16 36 13" src="https://github.com/millerjovon1/night-watch/assets/130570205/aac51bfa-185e-49a5-9b25-f1a9999db8ec">

<br>
App home: (https://movie-list-30de1af94e24.herokuapp.com/)
   

## Getting Started
### Setup

Install gems
```
bundle install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Acknowledgements
An Airbnb clone inspired by a mutual love for dogs.

## Team Members
- [Jovon Miller](https://www.linkedin.com/in/jovon-miller/)


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License


* ...
