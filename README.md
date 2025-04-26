# personal-normalizer-css

html {
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  margin-top: 0;
  margin-bottom: 0;
}

ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

a {
  list-style: none;
  text-decoration: none;
}

img {
  display: block;
  max-width: 100%;
  height: auto;
}

body {
  font-family: 'Montserrat', -apple-system, BlinkMacSystemFont, avenir next,
    avenir, segoe ui, helvetica neue, Cantarell, Ubuntu, roboto, noto, helvetica,
    arial, sans-serif;
  font-size: 18px;
  line-height: 1.2;
  letter-spacing: -0.015em;
  // padding-top: $size-header;

  &.lock {
    overflow: hidden;
  }
}
