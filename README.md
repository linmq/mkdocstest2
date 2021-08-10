## add an image with lightbox effect

```
<div class="gl-lightbox" itemscope itemtype="http://schema.org/ImageGallery">
  <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
    <a href="https://farm3.staticflickr.com/2567/5697107145_a4c2eaa0cd_o.jpg" itemprop="contentUrl" data-size="1024x1024">
      <img src="https://farm3.staticflickr.com/2567/5697107145_3c27ff3cd1_m.jpg" itemprop="thumbnail" alt="Image description" />
    </a>
    <figcaption itemprop="caption description">Image caption  1</figcaption>
  </figure>
</div>
```

For image lazy loading, add 
```
loading="lazy"
```
to img element.