# html5test1

Enter the following command into the terminal and press the `ENTER` key:

```bash
docker container run --platform linux/amd64 --rm -it --name "btp-setup-automator" "ghcr.io/sap-samples/btp-setup-automator:main"
```

You'll notice that the prompt in your terminal has changed, because you are now working inside the docker container, that you just started.
Now run the main script `btpsa` with the following command:

```bash
./btpsa -parameterfile 'https://raw.githubusercontent.com/rui1610/html5test1/main/btpsa/parameters.json' -globalaccount 'accountSubdomainId' -region 'region' -myemail 'emailAddress'
```
