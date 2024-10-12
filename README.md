# E-commerce Stock Analysis Project

## Project Overview:
This project focuses on analyzing stock levels in an e-commerce business to provide insights that can improve inventory management. The analysis looks into stock levels across various categories, sizes, colors, and designs, identifying overstocked and understocked items.

## Key Questions Addressed:
- **Category Analysis**: Which product categories are overstocked or understocked?
- **Size Analysis**: What are the most and least represented sizes in the stock?
- **Color Analysis**: Are there specific colors dominating the inventory or lacking representation?
- **Design Analysis**: Which designs have the most or least stock?

## Dataset:
The dataset includes stock information for different products, categorized by:
- **SKU Code**
- **Design No.**
- **Stock Level**
- **Category**
- **Size**
- **Color**

The data is used to assess current stock levels and provide recommendations for managing overstock and avoiding stockouts.

## Analysis and Insights:
The analysis is performed using Python, and visualizations are generated to support the findings:
- **Category**: Analyzed total and average stock across product categories.
- **Size**: Investigated stock distribution across different sizes.
- **Color**: Explored stock availability for various colors.
- **Design**: Reviewed top 20 designs by stock levels.

### Key Insights:
- **Overstocked Categories**: Some categories, such as `KURTA` and `KURTA SET`, are heavily overstocked and may need promotions or clearance sales.
- **Understocked Sizes**: Larger sizes (e.g., `XXXL`, `XXL`) are underrepresented and could lead to stockouts.
- **Overstocked Colors**: Colors like `Black`, `Pink`, and `Blue` dominate stock, while others like `AQUA GREEN` and `LEMON` are underrepresented.
- **Overstocked Designs**: Certain designs like `JNE3405` and `JNE1525` have significant overstock, suggesting a need for inventory adjustments.

## Recommendations:
- **Rebalance Stock**: Adjust stock levels to match customer demand. Focus on reducing inventory for overstocked categories, sizes, and colors, while increasing stock for underrepresented ones.
- **Promotional Strategies**: Offer discounts or promotions on overstocked products (e.g., `KURTA`, `Black`, `XS`) to clear inventory.
- **Future Inventory Management**: Implement dynamic inventory tracking to align stock levels with real-time sales trends and avoid future overstock/understock situations.

## Repository Structure:

