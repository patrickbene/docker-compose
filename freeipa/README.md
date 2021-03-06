# docker-compose FreeIPA

> Docker stack to have a FreeIPA server without DNS. This stack is a "simple" LDAP server.

## :factory: Requirements

* linux host (tested successfully on Ubuntu 18.04 & 20.04, Debian 9 & 10)
* docker >= 18.x

## :rocket: How to use

Clone this repo where you want with this line :

```bash
git clone https://github.com/Mettmett/docker-compose.git:freeipa
```

You need to edit the file `.env` at the source folder to modify the values of some vars.

After that when you're all set, press the red button to initiate :fire: !

```bash
docker-compose pull && docker-compose up -d && docker-compose logs -f
```

## :star: Author

Made by Julien HOMMET :fr: for [ComputerZ Solutions](https://computerz.solutions/)

* Twitter: [@_ComputerZ](https://twitter.com/_ComputerZ)
* GitHub: [Mettmett](https://github.com/Mettmett)

## :wrench: Support & Contribution

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## :moneybag: Licence

[MIT](https://choosealicense.com/licenses/mit/)

## :anchor: Misc

More infos at [https://computerz.solutions/docker-compose-freeipa/](https://computerz.solutions/docker-compose-freeipa/)
