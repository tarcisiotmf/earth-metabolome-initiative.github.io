# EMI Website

https://www.earthmetabolome.org/

## How to contribute ?

### Do you have a Github account ?

- Yes : Go to [Contribute after login to Github](#contribute-after-login-to-github)
- No : Go to [Do you want to create a Github account ?](#do-you-want-to-create-a-github-account)

### Do you want to create a Github account ?

- Yes : Go to [Create a Github account](#create-a-github-account)
- No : Go to [Contact us directly](#contact-us-directly)

### Create a Github account 

Go there https://github.com/signup and follow instructions.
You can then move to [Contribute after login to Github](#contribute-after-login-to-github)

### Contribute after login to Github

Two options here:

- Join the [EMI Github organization](https://github.com/earth-metabolome-initiative). For this we need your github username. Please send it to us at contact@earthmetabolome.org
We will send you an invite link. Once you accepted the invite you are able to directly contribute to the [EMI Github organization](https://github.com/earth-metabolome-initiative).

- Without joining the organization you should still be able to contribute but this will require you to make a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) each time you contribute. 

In both cases you should find your respective folders [here](https://github.com/earth-metabolome-initiative/earth-metabolome-initiative.github.io/tree/main/content/authors). 

### Contact us directly

You can directly send us your bio and details at contact@earthmetabolome.org. We will update them.


## Instruction to build and preview locally

Clone this repository and navigate to the local directory.

```
git clone https://github.com/earth-metabolome-initiative/earth-metabolome-initiative.github.io.git
cd earth-metabolome-initiative.github.io
```

Run hugo from the root directory.
You will need to have [hugo](https://gohugo.io/) installed first. 
You can install it directly in your system, see instructions here https://gohugo.io/installation/

Then you can directly run the hugo server by:

```
hugo server
```

Alternatively you can install using the following [Docker](https://www.docker.com/) image https://hub.docker.com/r/klakegg/hugo and run the server using the following command

```
docker run --rm -it \
  -v $(pwd):/src \
  -p 1313:1313 \
  klakegg/hugo:0.101.0-ext-ubuntu \
  server
```

Both options (local install or docker) should serve the website locally at http://localhost:1313/


