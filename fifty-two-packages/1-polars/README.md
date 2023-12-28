# Polars

- [Website](https://pola.rs/)
- [Github repo](https://github.com/pola-rs/polars)


<img src="https://fiftytwo.s3.us-east-2.amazonaws.com/polars.png" width="20%">

### Summary 

[Pandas](https://pandas.pydata.org/) (the Python package) is a great easy-to-use library for exploring and apply transformations to dataframes. However, one of its limitations is that it doesn't perform well with larger datasets. Pandas stores data in-memory and has a memory limit of 100GB. 

For use cases where you're dealing with data beyond the 100GB memory threshold, this is where Polars shines. Polars, which was built with Rust and uses Apache Arrow's columnar format, is said to execute common operations [10-100 times faster](https://blog.jetbrains.com/dataspell/2023/08/polars-vs-pandas-what-s-the-difference/#:~:text=As%20you%20can%20see%2C%20Polars,out%2Dof%2Dmemory%20errors.) than Pandas . With Polars' Lazy DataFrame, we can also handle larger-than-memory data beyond the 100GB threshold. 

### Review 

**Overall: A**

- Documentation: A
- Ease of use: A

I really enjoyed using Polars! It felt very similar to using PySpark and Pandas, and was easy to get up and running. If you're new to Polars, I highly recommend starting with the user guide. It was very well put together and gave a good overview of Polars' main features. 

Polars doesn't have the strong community support as Pandas, so there were some issues that took a while to debug. Stack Overflow sometimes gave me clues, but it definitely took me longer than usual to figure out why some of my code was throwing an error. 

Overall, I think Polars is great and I can't wait to test it out on larger datasets at work.