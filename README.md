# markiewicz_julian_website

Repository with code of my website build with HUGO. If you want to see the final product go [here](https://markiewiczjulian.github.io/).

This website was heavily inspired by shibumi [hugo-theme-hello-friend-ng](https://github.com/shibumi/hugo-theme-hello-friend-ng) and panr [hugo-theme-hello-friend](https://github.com/panr/hugo-theme-hello-friend) themes.

# How to run

To run this website locally you should install Hugo at least version 0.74.x (extended version). After this you can run

`hugo server -t hello-friend-ng`

this will spin up the server with everything you will need. Alternatively you can use only the theme. In such case create new empty hugo site with:

`hugo new site quickstart`

and move whole directory `/YOUR_PROJECT_ADDRESS/themes/hello-friend-ng` to the themes folder in your new application. Then you can run your site.

# How to use

This website works similar to the original that was based on (look [here](https://github.com/shibumi/hugo-theme-hello-friend-ng) and [here](https://github.com/panr/hugo-theme-hello-friend)), so I will not describe all options that can be used in conf.toml. I will however leave the example toml file config_example.toml in root of project which describes all options that can be defined for whole site.

Two noticeable differences are the projects directory which allows you to add projects with description, image (there is also option to click and show the image in full resolution) and url to project.

To add image to the project site add `mainimg` property in front matter and specify the image url or path.

To add the repository address to the project you can use `codeaddress` property.
