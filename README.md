# Smart India Hackathon Workshop
# Date: 25-11-26
## Reference Number: 26011090
## Name: M.Nithish

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
We propose MAATRAM, a web-based platform that helps farmers find buyers for their unsold agricultural produce before it goes to waste.

Many farmers face problems when their harvested crops do not get sold on time. Sometimes buyers cancel orders, market prices fall, or there is not enough demand. As a result, farmers may lose both their hard work and money.

Our idea is to help farmers find another way to sell their produce instead of letting it go to waste.

Farmers can enter details such as crop name, quantity, harvest date and storage conditions. The system will use this information to identify produce that may need urgent selling and alert the farmer.

If produce remains unsold, the platform will help find other possible buyers, such as nearby shops, supermarkets, hotels and food-processing units. It will also help farmers compare selling prices and transportation costs.

If the produce cannot be sold through the usual market, the platform will suggest other options, such as discounted sales, bulk buyers, food-processing units or suitable food donation organisations.

We will also include a simple assistant that gives suggestions based on the available quantity, location and market information.

The main aim of MAATRAM is not just to connect farmers with buyers. It is to help them find a solution when their harvested produce has no buyer, reducing financial losses and unnecessary food wastage.

## Technical Approach
We plan to develop MAATRAM as a web application using HTML, CSS, JavaScript and React.js for the frontend. Python and Django will be used for the backend, and MySQL will be used to store farmer, buyer and crop details.

We will use Python libraries such as Pandas and Scikit-learn to analyse inventory information and identify produce that may need urgent attention. Google Maps API will help display buyer locations and suggest suitable routes. Chart.js will be used to display information through charts.

First, farmers will register on the platform and enter their crop details, including the quantity, harvest date and storage conditions. The system will maintain records of available, sold and unsold stock.

Next, the system will check the available inventory and identify produce that may need to be sold quickly. It will then look for possible buyers based on crop type, quantity and location.

Farmers can compare the available buyers, selling prices and estimated transportation costs. If a suitable buyer is not found, the system will suggest other options such as discounted sales or food-processing units.

Farmers can review the suggestions and choose the option they prefer. A dashboard will display stock details, sales information and the quantity of produce successfully redirected to other buyers.

For the initial prototype, we plan to use sample farmer and buyer details. Later, we can connect the platform with real farmers, FPOs and buyers.

## Feasibility and Viability
MAATRAM can be developed using technologies that are already available. Since our team is planning to build a web application, we can start with basic features and improve the platform step by step.

The first version will include farmer registration, harvest details, stock monitoring and buyer matching. We can use sample data to demonstrate how the system works during the initial development stage.

One of the main challenges may be getting accurate information about market demand and available buyers. Farmers may also forget to update their stock details. Another challenge is finding suitable buyers quickly without increasing transportation expenses.

To handle these problems, we plan to keep the process of entering harvest details simple and allow farmers to update their stock whenever needed. We will use crop-specific estimates and storage information to identify produce that may need urgent attention.

The platform will suggest buyers based on their location, required quantity and expected transportation costs. Farmers will be able to review and approve suggestions before confirming any transaction.

We can first demonstrate the project with sample data and then test it with a small group of farmers and buyers. This will help us understand what needs improvement before expanding the platform.

## Impact and Benefits
MAATRAM is mainly focused on helping farmers who struggle to sell their harvested produce on time.

The platform can help farmers find alternative buyers for unsold crops and reduce the chances of losing money. It also gives them more selling opportunities and helps them compare prices before choosing a buyer.

Buyers can use the platform to find available agricultural products directly from farmers. This may reduce unnecessary intermediary costs and create better opportunities for both farmers and consumers.

The project can also support small and medium-scale farmers by connecting them with shops, retailers, food-processing units and FPOs.

From an environmental point of view, MAATRAM can help reduce avoidable food wastage by finding alternative uses for surplus produce. Suitable food can also be redirected through authorised donation organisations.

Our goal with MAATRAM is simple: when a farmer has produce that is not selling, the farmer should have another option instead of accepting a loss.

## Research and References

1. e-NAM – National Agriculture Market: https://enam.gov.in/

2. AGMARKNET – Agricultural Marketing Information Network: https://agmarknet.gov.in/

3. Ministry of Agriculture and Farmers Welfare: https://agriwelfare.gov.in/

4. Food Safety and Standards Authority of India: https://www.fssai.gov.in/

5. India Meteorological Department: https://mausam.imd.gov.in/

6. Python and Scikit-learn Documentation: https://scikit-learn.org/

7. Google Maps Platform Documentation: https://developers.google.com/maps

These websites and resources will help us understand agricultural markets, food safety, weather information and the technologies required to develop MAATRAM.
