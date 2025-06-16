# Running the Presentation Website

The presentation website is a static website made with `hugo` static site generator. To install `hugo` follow these [instructions](https://gohugo.io/installation/) for your operating system.

After installing `hugo`, you need to pull the repository with submodules to pull the website's themes. You can do this using

```
git clone --recurse-submodules https://code.cs.umanitoba.ca/comp3350-summer2025/a01-g10-shift-happens.git
```

or if you've already cloned

```
git pull --recurse-submodules
```

Then `cd` to the `website` directory of the project:

```
$ cd website
$ hugo server
```

Then open the localhost url given on your browser.
