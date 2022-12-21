# StyleDesignWithCSS
CSS styling
===========
1. inline style (within tag you need to mention <tag style="key:value">)
2. Style tag (<style>................ </style>)
3. External style (<filename>.css file)


CSS Specificity >>
=================
inline style > Style tag > External style


/* Element Selector examples  ==> For All similar Element */
header{
    background-color: #ff0000;
    margin-bottom: 5px;
    margin-top: 0;
    padding: 10px;
    /* border: 10px solid rgba(0, 0, 0, 1); */
    /* border: 10px solid rgb(0, 0, 0); */
    
    border: 10px solid #fff;
    border: 10px solid #ffffff;
    border: 10px solid hsl(0, 0, 0);
    border: 10px solid #000;
}

/* Multiple Element Selectors examples */
p,h2,h1{
    color: gray;
}

/*ID Selector  ==> For unique */
#subtitle{
    font-size: xx-large;
    margin:0;
}

/*class Selector Examples ==> For Specific Group */
.post{
    border-left: 4px solid green;
}
