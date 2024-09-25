The dataset I chose is about laptops and their prices. These are the data in the columns:

Laptop: The product name and specifications.
Status: The status of the laptop. 
Brand: The brand of the laptop 
Model: The model of the laptop.
CPU: The processor information.
RAM: The amount of RAM in GB.
Storage: The storage in GB.
Storage type: The type of storage.
GPU: The graphics processing unit model.
Screen: The screen size in inches.
Touch: If the laptop has a touchscreen or not.
Final Price: The final price of the laptop.

Dataset Source: https://www.kaggle.com/datasets/juanmerinobermejo/laptops-price-dataset

Main Inquiry:
What are the main factors that affect laptop pricing?

Sub-questions:
Is there a significant price difference between laptops with different CPU models?
Does having a dedicated GPU impact laptop prices significantly compared to laptops without GPUs?
How does the amount of RAM impact laptop prices?

Laptop Dataset Cleaning:
Missing values: Storage, GPU, and Screen values.

How I handled these:
Storage type: Showing many missing values, I marked them as "Unknown."
GPU: A lot shows missing values, most likely meaning they don’t have a GPU. So, I replace these with "No GPU."
Screen: Filled in the missing screens with “median screen size.”
There were no duplicate rows, and all columns had correct categorical and numeric variables.

Interpretation:
Is there a significant price difference between laptops with different CPU models? The High-end CPUs such as the Intel Core i9 and Apple M1/M2 Pro compare to relatively higher prices than lower-tier CPUs such as the Intel Core i3 or i5.

Does having a dedicated GPU impact laptop prices significantly compared to laptops without GPUs? Laptops with dedicated GPUs, such as gaming laptops, are usually more expensive, almost doubling the cost of laptops without a GPU.

How does the amount of RAM influence laptop prices? Laptops with 16 GB of RAM are much more expensive than those with lower RAM, like 4 GB or 8 GB. Interestingly, laptops with 12 GB of RAM have a slightly lower average price than those with 8 GB.

Summary:
From what I gather from everything, with CPU’s higher-end CPUs like the Intel Core i9 and AMD Radeon 9 have significantly increased laptop prices compared to lower-tier models like the Intel Core i3 or i5. With GPUs laptops with GPUs are twice as expensive as laptops without them. Lastly, with regard to RAM, laptops with around 16 GB of RAM are way more expensive compared to 4 GB and 8 GB laptops.

Further Exploration:
I could have explored the impact of storage type and capacity on pricing. Or how multiple factors interact to affect prices.
