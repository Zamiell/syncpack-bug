# `syncpack-bug`

Steps to reproduce:

```sh
git clone git@github.com:Zamiell/syncpack-bug.git
cd syncpack-bug
npm ci
npx syncpack list-mismatches
```

We can see that the depednency is already up to date, but syncpack throws and error and says that it is not up to date.
