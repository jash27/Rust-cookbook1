# Rust Cookbook
This is the code repository for [Rust Cookbook](https://www.packtpub.com/application-development/rust-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781785880254), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Sign up to our emails for regular updates, bespoke offers, exclusive discounts and great free content.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```

    println!("Entering a block \n");
    {
        // This is equivalent to `use deeply::nested::sample_function as sample_function`.
        // This `sample_function()` will shadow the outer one.
        use deeply::nested::sample_function;
        sample_function();

        // `use` bindings have a local scope. In this case, the
        // shadowing of `function()` is only in this block.
        println!("Leaving the block \n");
    }

    sample_function();
```



## Related Products
* [Mastering Rust](https://www.packtpub.com/application-development/mastering-rust?utm_source=github&utm_medium=repository&utm_campaign=9781785885303)

* [Rust Essentials](https://www.packtpub.com/application-development/rust-essentials?utm_source=github&utm_medium=repository&utm_campaign=9781785285769)

* [Rust Essentials - Second Edition](https://www.packtpub.com/application-development/rust-essentials-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788390019)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
