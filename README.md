# Quiz-app

![Screenshot_20211015_005819](https://user-images.githubusercontent.com/83106116/137383800-d269f82e-3049-4e0a-a17b-25831705f9ab.png)

![Screenshot_20211015_005922](https://user-images.githubusercontent.com/83106116/137383845-23001086-a2a4-4e4e-8144-7b002911a72b.png)

A quiz app build using OPENTB api and Javascript.

Limited resource application

## specifications

    * Dark and light theme
    * Easy medium hard levels
    * Questions based on different topics

## Docker Instructions

If you haven't installed [Docker](https://www.docker.com/products/docker-desktop) already, then you can get it from [here](https://www.docker.com/products/docker-desktop). After installing it, create an account in Docker and copy the username.

To run the app in a docker container, follow the given steps:

- Clone this repository

  ```bash
  git clone https://github.com/{your USER_NAME}/quiz-app.git
  ```

- Navigate to the project directory
  ```bash
  cd quiz-app
  ```
- Replace <strong>USERNAME</strong> with your own username and build the docker image
  ```bash
  docker build -t <USERNAME>/quiz-app:1.0 .
  ```
- Open up the terminal at the project directory, replace <strong>USERNAME</strong> with your own username and run the following command:
  ```bash
  docker run -d -p 8080:8080 <USERNAME>/quiz-app:1.0
  ```

# doubts

- Send a mail to the mail in my dashboard
- Or by creating wiki

# Contribution

- Open for contribution
- To contribute:
  - Fork the repo
  - Clone the repo
  - Make your changes
  - Commit and push the changes
  - Generate a Pull Request
  - on commit name must be like #issue number

## Sit back and relax while your PR gets merged

### don't just fork start it too

### smash the star button

# Leave a star if you liked the app!

## hacktoberfest

![Hacktoberfest_x_Spotify_2021_Final_Blog-Twitter-Discord_B](https://user-images.githubusercontent.com/58719884/135654867-afa18ae2-f239-4a0a-b1fd-6df7d92b8dac.png)
