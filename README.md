





### Browser

You only need the build/kuromoji.js and dict/*.dat.gz files

Install with Bower package manager:

    bower install kuromoji

Or you can use the kuromoji.js file and dictionary files from the GitHub repository.


In your JavaScript:

    kuromoji.builder({ dicPath: "/url/to/dictionary/dir/" }).build(function (err, tokenizer) {
        // tokenizer is ready
        var path = tokenizer.tokenize("すもももももももものうち");
        console.log(path);
    });



