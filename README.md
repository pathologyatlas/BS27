






```
r language BS27, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis lenfanjiektazi duodenum TR, echo = (language == "TR")
## BS27 - lenfanjiektazi duodenum {#sec-BS27 }
```


```
asis lymphangiectasia duodenum EN, echo = (language == "EN")
## BS27 - lymphangiectasia duodenum {#sec-BS27 }
```






```
r BS27 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS27-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS27/HE.html",
  file = "./screenshots/BS27-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS27/HE.html](https://images.patolojiatlasi.com/BS27/HE.html)





```
asis, echo = (language == "TR")

**lenfanjiektazi duodenum**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS27-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS27/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS27/HE.html)
```

```
asis, echo = (language == "EN")

**lymphangiectasia duodenum**

[![Click for Full Screen WSI](./screenshots/BS27-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS27/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS27/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS27/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS27/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```






:::::





