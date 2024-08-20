# 🍕 Pizza Hut Sales Analysis Project

Welcome to the Pizza Hut Sales Analysis project! This project leverages MySQL to analyze sales data and extract meaningful insights through a series of SQL queries. Each query addresses specific business questions, helping to understand sales trends, revenue generation, and customer preferences.

## 📂 Project Structure

The project is organized around solving 12 key business questions using SQL:

1. **📝 Retrieve the total number of orders placed:**
   - Count the total orders in the `orders` table.

2. **💰 Calculate the total revenue generated from pizza sales:**
   - Compute total revenue by multiplying the quantity sold by the price of each pizza.

3. **🏆 Identify the highest-priced pizza:**
   - Find the pizza with the highest price in the dataset.

4. **📏 Identify the most common pizza size ordered:**
   - Determine the most frequently ordered pizza size.

5. **🥇 List the top 5 most ordered pizza types along with their quantities:**
   - List the top 5 pizza types based on the quantity ordered.

6. **🍕 Find the total quantity of each pizza category ordered:**
   - Calculate the total quantity ordered for each pizza category.

7. **⏰ Determine the distribution of orders by hour of the day:**
   - Analyze how orders are distributed throughout the day.

8. **📊 Category-wise distribution of pizzas:**
   - Show the distribution of pizzas across different categories.

9. **📅 Group orders by date and calculate the average number of pizzas ordered per day:**
   - Calculate the average daily pizza orders.

10. **💸 Determine the top 3 most ordered pizza types based on revenue:**
    - Identify the top 3 pizza types generating the most revenue.

11. **📈 Calculate the percentage contribution of each pizza type to total revenue:**
    - Determine the revenue contribution percentage for each pizza category.

12. **🔄 Analyze the cumulative revenue generated over time:**
    - Track the cumulative revenue over time.

## 🗃️ Dataset

The analysis is based on a hypothetical dataset consisting of the following tables:

- **`orders`**: Contains order details, including `order_id`, `order_date`, and `order_time`.
- **`orders_details`**: Contains details about items in each order, including `order_details_id`, `order_id`, `pizza_id`, and `quantity`.
- **`pizzas`**: Contains details about each pizza, including `pizza_id`, `pizza_type_id`, `size`, and `price`.
- **`pizza_types`**: Contains details about pizza types, including `pizza_type_id`, `name`, and `category`.

## 🛠️ Queries

The SQL queries used to answer each of the 12 questions are included in this repository. Each query is meticulously crafted to extract insights from the dataset, showcasing the power of SQL in data analysis and business intelligence.

## 🔍 Conclusion

This analysis provides valuable insights into Pizza Hut's sales patterns, revenue, and customer preferences. The queries demonstrate how SQL can be applied to uncover data-driven insights that inform business strategies.

## 🚀 Usage

To replicate this analysis:

1. **Clone** this repository.
2. **Import** the dataset into a MySQL database.
3. **Run** the provided SQL queries to explore the data.

Feel free to modify the queries to explore other aspects of the sales data!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
