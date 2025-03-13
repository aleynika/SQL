# SQL Portfolio 🗂️

Welcome to my SQL portfolio! This repository showcases my work with SQLite through various projects, where I’ve applied fundamental and advanced SQL techniques to analyze data and derive insights. Below is a brief description of the projects and the SQL techniques used. 🚀

## Projects 📊

### 1. **Superstore Inventory & Rating Analysis** 🏪
This project involves managing a database for product details, including pricing, stock quantities, and customer ratings. I executed a series of SQL queries to analyze inventory levels, identify top-rated products, and optimize business decisions.

#### Key SQL Techniques:
- **Aggregate Functions**: Used `SUM()` to calculate total stock available, `MAX()` and `MIN()` for analyzing product ratings and pricing, allowing insights into inventory and sales trends.
- **Filtering**: Applied `WHERE` clauses to isolate products needing replenishment based on stock quantity thresholds, helping to identify which products are understocked.
- **Ordering & Grouping**: Utilized `ORDER BY` and `GROUP BY` for sorting data by price and product category, optimizing how data is viewed and interpreted.

---

### 2. **Baked Goods Inventory Analysis 🍰**
In this project, I created and populated a database for various baked goods, then used SQL queries to manage and analyze the inventory.

#### Key SQL Techniques:
- **Data Insertion & Table Design**: Employed `INSERT INTO` for populating the table and defined a table schema with proper data types to ensure integrity.
- **Aggregate Functions**: Used `SUM()` to get the total available stock across all baked goods, providing an overview of inventory levels.
- **Filtering & Sorting**: Applied `WHERE` and `ORDER BY` to focus on specific products needing replenishment and to sort products by price, giving a clearer view of product availability.
- **Conditional Logic**: Applied `CASE` statements to categorize products based on their `Attack` and `Defense` values, enabling a dynamic way to classify product attributes.

---

### 3. **Pokémon Stats Analysis ⚔️**
This project focuses on analyzing Pokémon statistics by primary type, including determining the highest and lowest stats for various categories like HP, Attack, Special Attack, Special Defense, and Speed.

#### Key SQL Techniques:
- **Aggregation**: Used `MIN()` and `MAX()` functions to find the highest and lowest stats by primary type, providing insights into Pokémon strength and weaknesses across categories.
- **Group By**: Leveraged the `GROUP BY` clause to analyze stats by Pokémon type, which helps categorize the Pokémon based on their type and strengths.
- **Conditional Statements**: Used `CASE` to categorize Pokémon based on their `Attack` and `Defense` values, identifying which types are stronger or weaker.
- **Subqueries**: Applied subqueries to retrieve Pokémon based on specific conditions, such as having higher attack and defense stats.

---

## License 📜

This project is licensed under the MIT License - see the [LICENSE](https://github.com/aleynika/SQL/blob/main/LICENSE) file for details.

---

Feel free to explore the SQL queries and gain insights into how I approach data analysis using SQLite. I’m continuously learning and excited to apply my skills in real-world data analysis and business decision-making contexts. 💻✨
