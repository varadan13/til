# Do this to bump the graph api version of facebook sdk

```html
<script>
  window.fbAsyncInit = function() {
    FB.init({
      appId            : 'your-app-id',
      xfbml            : true,
      version          : 'v19.0'
    });
  };
</script>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_US/sdk.js"></script>
```
   
> resource : https://developers.facebook.com/docs/javascript/quickstart/
