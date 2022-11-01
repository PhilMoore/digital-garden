```
<div class="banner-video">
 <video autoplay loop muted playsinline>
    <source src="https://cdn.shopify.com/videos/c/o/v/c2201bede2f5423d9bd4e8e87b6c2c5b.mp4">
  </video>
<div class="banner-video-text"><h2>Childrenswear Reinvented</h2><h3>Welcome to All Things Dylan</h3></div>
</div>



```


### Video CSS

```

.banner-video video {
    width: 100%;
}
.banner-video-text {
    position: absolute;
    top: 0;
    text-align: center;
    max-width: 1200px;
    padding: 0 20px;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    margin: auto;
    left: 0;
    right: 0;
    flex-direction: column;
}

.banner-video-text h2 {
    color: #fff;
    display: block;
    width: 100%;
    margin: 0;
}
.banner-video-text h3 {
    color: #fff;
    margin: 10px 0 0;
    font-size: 20px;
    font-weight: 400;
}

```