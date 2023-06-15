# About The Project
---
### Do-gether
Sharing your TODO-LIST with others!<br>
Do-gether은 투두리스트를 다른사람들과 공유할 수 있도록 도와주는 동기부여 서비스입니다.
<br><br>

### Bulit With
- React
- Material-ui
- Node.js
- Mysql
- Unsplash Image API

# HOW TO USE
---
You can come here and use DO-GETHER.<br>
[`http://www.dogether.tk`](http://www.dogether.tk)
* Now suspended
![main](https://github.com/marooo326/Do-gether-legacy/assets/121790935/0d5ef038-6797-4fd4-adb1-4d89adc31c5d)

<br><br>

# HOW TO INSTALL
---
#### First, clone this project
`git clone http://khuhub.khu.ac.kr/2019102153/Do-gether.git`
<br>

and execute this command.
```sh
npm install
cd client
npm install
```
<br>

#### Second, install YARN.
On Debian or Ubuntu Linux, you can install Yarn via our Debian package repository.
<br>

You will first need to configure the repository:
```sh
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
```
<br>

On Ubuntu 16.04 or below and Debian Stable,<br>
you will also need to configure the NodeSource repository to get a new enough version of Node.js.
<br>

Then you can simply:
`sudo apt update && sudo apt install yarn`<br><br>
Reference from [`YARN`](https://yarnpkg.com/en/docs/install)
<br>

#### Third, add "database.json"
you should add `database.json` in the following format.
```sh
{
    "host":"host name",
    "user":"user name",
    "password":"password",
    "port":"port number",
    "database":"table name"
}
```
<br>

#### Finally, you can use DOGETHER by using `yarn dev` in `Do-gether` directory.
<br><br>

#### Error
In my case, an unknown error occurred when running `yarn dev`.<br>
So I solved it as follows.
<br><br>
Execute this command.
`vi Do-gether/client/node_modules/react-scripts/config/webpackDevServer.config.js`
<br><br>
And change the `disableHostCheck: ...` option to `disableHostCheck: true`.
![error](https://github.com/marooo326/Do-gether-legacy/assets/121790935/18981df5-72eb-4f8e-84db-8b4a7cf2b1f2)

<br><br>


# LISENCE
---
Do-gether is free software, and may be redistributed under the terms specified in the MIT LICENSE.