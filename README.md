# hello-rocket

Hello for the [Rocket](https://rocket.rs) library and [Heroku](https://heroku.com) with Rust!

## Setup

1. Clone this repo.
> git clone https://github.com/NeuroWhAI/hello-rocket.git

1. Go to 'hello-rocket' directory.
> cd hello-rocket

1. Set nightly version.
> rustup override set nightly

1. Create app project on [Heroku](https://heroku.com).

1. Connect to app.
> heroku login  
> heroku git:remote -a existing-project-name

1. Set buildpack.
> heroku buildpacks:set https://github.com/emk/heroku-buildpack-rust.git

## Build & Run

1. Build with cargo.
> cargo build

1. Run.
> cargo run

1. Open 'http://localhost:8000'.

## Deploy

1. Commit new change.
> git add .  
> git commit -m "Change something"

1. Push to Heroku.
> git push heroku master

1. Wait for the deployment to complete.

## Custom

- Edit whatever you want.
- You can change compiler version in Heroku by modifying the 'rust-toolchain' file.
