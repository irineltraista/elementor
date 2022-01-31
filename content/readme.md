Set elementor content full width while keeping a max size for big screens. 

1. Give an id (e.g. #limitwidth) to the section you want to limit full width. (make sure that the section is set to full width layout)
2. Add this css on your page css or in global css. (change values to the desired ones)

**CSS:
**

```

#limitwidth .elementor-row {
  max-width: 1440px!important; //Here you can set up your maximum width
  }
  #limitwidth .elementor-container {
  justify-content: center!important; 
  }
```

3. Congrats, you have a limited content width for your elementor containers. 
In order to replicate this for multiple containers, you can assign the id to them.
