# web_layout
Simple website layout for web dev by dept-11.com

```r
# install package once
install.packages("servr")

# set port
options(servr.port = 4321)

# start
servr::httd()

# stop
servr::daemon_stop(1)
```

If you want to render \*.Rmd (Rmarkdown) files into \*.html, you can use the Build RStudio pane -> Build Website for all pages, or individually you can open index.Rmd and click the Knit button, or in Console use:

```r
rmarkdown::render_site()
```

But please feel free to disregard all Rmarkdown stuff here and just go with whatever HTML building tools you want to render the splash page, as long as the links are correct to the Shiny app (a la `http://{root}/?nav=Projects`).

#SCSS Development
1. Open Terminal/Shell
2. Navigate to /scss
3. Run `npm install`
4. After complete, run `gulp`
5. This will run and generate a new styles.css in the root.