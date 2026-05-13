# ProjectOmu Home Webpage w/ Hugo

This is the [Hugo](https://gohugo.io) content and structure used to build our homepage. You will need to have Hugo installed and added to your `PATH` if you wish to contribute. Please read over some of the quickstart documentation if you wish to contribute.

The first part of contributing will require downloading any and all submodules used within the compilation of this repository. These **should** be under `themes/`. You can do so by using the following command in your terminal.

```
git submodule init
```

> Our current Hugo theme is [Blowfish](https://github.com/nunocoracao/blowfish).

## Hugo Building/Testing

If you'd like to run the server, it is suggested to follow this simple process. You can build the site without rendering it for any small change by running `$ hugo` inside the project. This should generate all that you need under `public/` and `resources/`. If you'd like to make changes and watch them update in real time, it is suggested to run `$ hugo server` so that you can make changes and see them update in real time.

The website will automatically update when the `master` branch is pushed.

## Contributing

For the time being, we are not accepting contributions to this repository unless it is a fix or critical issue. This is subject to change once the webpage is fully up and running.