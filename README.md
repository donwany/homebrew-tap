## Installation

```shell
# Add tap to your Homebrew:
$ brew tap donwany/tap

# Install tool:
$ brew install aero

$ git clone https://github.com/donwany/aero
$ cd aero/
$ git tag v1.0.1 # our new tag
$ git push --tags # push tags to remote

$ wget https://github.com/donwany/aero/blob/main/aero_v0.1.1-next_Darwin_arm64.tar.gz

$ wget https://github.com/donwany/aero/archive/refs/tags/v1.0.0.tar.gz

shasum -a 256 v1.0.0.tar.gz 

```
```shell
brew tap donwany/tab
brew install aero
aero weather --city Dallas --apikey $APIKEY

Response Status:  200 OK
{
 "Func": "Atoi",
 "Num": "{\"coord\":{\"lon\":-96.7836,\"lat\":32.7668},\"weather\":[{\"id\":804,\"main\":\"Clouds\",\"description\":\"overcast clouds\",\"icon\":\"04d\"}],\"base\":\"stations\",\"main\":{\"temp\":308.53,\"feels_like\":313.93,\"temp_min\":306.96,\"temp_max\":310.46,\"pressure\":1017,\"humidity\":48},\"visibility\":10000,\"wind\":{\"speed\":2.68,\"deg\":135,\"gust\":6.26},\"clouds\":{\"all\":100},\"dt\":1628895400,\"sys\":{\"type\":2,\"id\":2018848,\"country\":\"US\",\"sunrise\":1628855370,\"sunset\":1628903674},\"timezone\":-18000,\"id\":4684904,\"name\":\"Dallas\",\"cod\":200}",
 "Err": {}
}
```