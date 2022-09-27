# givr

### Our final project for the demo day at Le Wagon.<br><br>
Below you can see the dashboard where a user can post an item they no longer need or request an item they want. The dashboard allows users to direct message.

<img width="959" alt="Givr-screenshot-2" src="https://user-images.githubusercontent.com/92862939/192511159-e9a570af-6acc-436d-a2a5-1866947a7f04.png">

<br>
App home: https://givr.site
   

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
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
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
This project is licensed under the MIT License
