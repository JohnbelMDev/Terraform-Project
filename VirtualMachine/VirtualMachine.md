<h3>Ensure that you have Azure, Brew, and Terraform installed on your operating system. </h3>
<h4>If you’re using a Mac, you can check whether Azure, Brew, and Terraform are installed on your machine by following these steps: copy and paste the commands provided in your Mac terminal. </h4>

``` 
az --version 

```

``` 
brew --version 

```

``` 

Terraform --version 

```

<h3>If you don’t have any of the above installed, please copy and paste the following commands one at a time into your terminal. Wait for each installation to complete before moving on to the next command.</h5>

``` 
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

```

``` 
brew update && brew install azure-cli


```

``` 
brew tap hashicorp/tap

```

```

brew install hashicorp/tap/terraform

```
