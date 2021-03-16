
# PyThaiNLP Tutorials

[![Build status](https://ci.appveyor.com/api/projects/status/8n37h7c6gmng825s/branch/master?svg=true)](https://ci.appveyor.com/project/wannaphongcom/tutorials/branch/master)


The repository contains tutorial notebooks for the official documentation website.

All the tutorial notebook are presented as sphinx-style document at:

[https://pythainlp.github.io/tutorials](https://pythainlp.github.io/tutorials)

## Contributing Guideline

1. Upload notebook to `source/notebooks` in  `dev`
2. Create a pull request to `master` branch
3. After the pull request is merged, the new notbook will be generated automatically and uploaded to thainlp.org/pythainlp/tutorials


## Generate documentation

1. Run `make html` to build HTML document from notebooks 
2. The generated HTML files will be in `build/html`
