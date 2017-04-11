# Baskerville Child Theme - Add Sidebar to Homepage

Upload this as a wordpress theme and you should have a sidebar on the Homepage of the great [Baskerville Wordpress theme](https://wordpress.org/themes/baskerville/).

The sidebar only shows up desktop when the screen width is > 1000px. If you require the sidebar on mobile then inject the following CSS into your website.

```
/* CSS */
@media (max-width: 1000px){
  .home-sidebar{
    display: block !important;
    width: 100%;
    padding-left: 20px;
    padding-right: 20px;
  }
  .sidebar{
    width: 100%;
    margin-top: 30px;
    padding: 0;
    display: block !important;
  }
  .fright.home-sidebar,
  .sidebar.fright{
    float: none !important;
  }
}
/* END CSS */
```

I am not the author of Baskerville, nor am I in any way affiliated with the theme, or it's author. I just created a child-theme to include a Sidebar on the Homepage.
