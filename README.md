# Welcome to RNA Editing Plus

Due to funding issues, RNA Editing Plus now cannot afford the maintenance fees. As a consequence, we have to shutdown the web server. To minimize the lost, we have developed an offline version of REP, which can be cloned from [GitHub](https://github.com/RNAEDITINGPLUS/main).

## How to deploy RNA Editing Plus

RNA Editing Plus can be divided into two parts: web interface and computing nodes. The web interface needs the support from Apache and MySQL, while computing nodes require a lot of dependent packages. To simplify the installation, we provide two install scripts to handle this issue, here is the tutorial:

### 1. First: Clone REP
```
git clone https://github.com/RNAEDITINGPLUS/main.git
```
### 2. Second: Setup database and web server
```
cd main
chmod +x deploy.sh
./deploy.sh
```
### 3. Third: Configure computing nodes
**Before configuring computing nodes, please copy the node folder to the target machine.**
```
cd node
chmod +x nodedeploy.sh
./nodedeploy.sh
```

### Support or Contact

Having trouble with RNA Editing Plus? Check out our [documentation](https://github.com/RNAEDITINGPLUS/docs/blob/master/TUTORIAL.pdf) or [contact support](mailto:zyc@rnaeditplus.org) and we’ll help you sort it out.
