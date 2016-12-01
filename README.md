![Slim from scratch](https://guides.nanobox.io/assets/quickstart-icons/slim.png)

# Slim from scratch

Run a Slim app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-slim.git

# cd into the slim app
cd nanobox-slim
```

## Run the app

```bash
# Run slim as you would normally, with Nanobox
nanobox run php-server
```

## Check it out

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local slim.dev
```

Visit your app at <a href="http://slim.dev:8000" target="\_blank">slim.dev:8000</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where slim is installed,
php -v

# your packages are available,
composer show

# and your code is mounted
ls
```

## Now What?
For more details about running slim apps with nanobox visit [guides.nanobox.io/php/slim/](https://guides.nanobox.io/php/slim/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
