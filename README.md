## PHPUnit - The PHP Unit Testing framework
[![Docker Pulls](https://img.shields.io/docker/pulls/rvannauker/phpunit.svg)](https://hub.docker.com/r/rvannauker/phpunit/) [![Docker Stars](https://img.shields.io/docker/stars/rvannauker/phpunit.svg)](https://hub.docker.com/r/rvannauker/phpunit/) [![](https://images.microbadger.com/badges/image/rvannauker/phpunit:latest.svg)](https://microbadger.com/images/rvannauker/phpunit:latest) [![GitHub issues](https://img.shields.io/github/issues/RichVRed/docker-phpunit.svg)](https://github.com/RichVRed/docker-phpunit) [![license](https://img.shields.io/github/license/RichVRed/docker-phpunit.svg)](https://tldrlegal.com/license/mit-license)

Docker container to install and run phpunit

### Installation / Usage
1. Install the rvannauker/phpunit container:
```bash
docker pull rvannauker/phpunit
```
2. Run phpunit through the phpunit container:
```bash
sudo docker run --rm --volume $(pwd):/workspace --name="phpunit" "rvannauker/phpunit"
```

### Download the source:
To run, test and develop the PHPUNIT Dockerfile itself, you must use the source directly:
1. Download the source:
```bash
git clone https://github.com/RichVRed/docker-phpunit.git
```
2. Build the container:
```bash
sudo docker build --force-rm --tag "rvannauker/phpunit" --file phpunit.dockerfile .
```
3. Test running the container:
```bash
 $ docker run rvannauker/phpunit --help
```