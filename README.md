# Urbanic

## Week 1

Why is blockchain needed to solve this problem?
What demographics do you serve? What is the size of the market?
What other solutions are currently being used to address this problem? (other companies, workarounds, systems or processes that can compete with or substitute your product)
What are the geopolitical, cultural-social-economic factors that must be taken into consideration? What are some nuances and complexities that must be addressed?


## Week 2
1. **Who are your constituents/clients/users? (Create User Persona(s))**
 - *Paola*: She is a housewife dedicated to caring for her children and her husband.
He is 33 years old, he finished his degree in Nutrition but never practiced.
He likes to take care of his family and friends in whatever he can.

 - *Victor*:  He is 29 years old, manager of his own company. Is dedicated to selling software programs. He likes to take care of his pets and tries to help the environment

 - *Peter*: He is 45 years old, He works selling carton box and bottles to support his family

2. **What are their pain points?**
 - The increase in greenhouse gases is causing the melting of glaciers by raising the sea level. If this is maintained, people on the coast will be affected by losing their heritage and will be forced to migrate.

 - The high degree of pollution in cities is increasing the number of respiratory, skin and eye irritation diseases, decreasing the quality of life.

3. **What is your product's value proposition?**
 Urbanic is a system that through the use of blockchain technology, allows people to generate income by taking actions that benefit the environment thanks to the support of companies concerned about reducing their carbon emissions. 
Urbanic has 3 key components: companies, communities and people.

- **Companies**
Companies concerned about reducing their carbon emissions into the atmosphere participate by purchasing carbon credits through urbanic, these revenues are tokenized and put into circulation so that anyone who performs environmentally friendly actions can participate to earn a reward for their work.

- **Communities**
All regional communities whose objective is to stop or reverse climate change can participate as observers validating that the actions taken by the end users have a real impact on the environment while suggesting rules of operation according to the region where they are located.

- **End Users**
They are people concerned about the environment with a desire to have a green life, with their daily actions they help to stop or reverse climate change generating a verifiable impact for others, they receive rewards from companies for their contributions to motivate them to continue generating more benefits and an alternative income.

4. **What is your distribution and go-to-market strategy? Who can you partner with?**
See [See /GoToMarket.md](/GoToMarket.md)

5. **What are the risks associated with your solution?**
- Economic malfunction
- The final product is not accepted by customers or companies
- Companies or brands that do not want to support, weakening the economic model that is being proposed

6. **What is the impact of your solution? How will it be measured?**
- Promote recycling and reforestation
- Reduce the consumption of products that generate greenhouse gases through an economic model

7. **Define the technical specifications and development roadmap**

1. Landing design to collect emails and info from target users 
  1.1 Create Mailchimp account and setup signup form
  1.2 Inject the form into urbanic.world page
  1.3 Add google anayltics to start measuring how many time the user spends on the site
2. Implement python scraper to get air quality levels in Mexico cities
  2.1 Create an instance on Digitital Ocean and setup a linux environment
  2.2 Create Contract to store air quality info
  2.2 Run the script to start collecting the data and submit transactions to the air quality contract
  2.3 Create API endpoint to query the air quality data
3. Implement ERC20 token $URBN
  3.1 Implement API to mint tokens when users accredit some ecological action
  3.2 Implement API to burn tokens when some company or users pay for its ecological impact
  3.3 Implement API to know the price of one $URB based on the amount of trade and the air quality
4. Develop web and mobile application on react native and connect with Cello
  4.1 Implement View to register ecological activity and earn $URBN tokens
  4.2 Implement QR code to validate that some user perform the ecological activity 
  4.3 Implement View to burn and transfer $URNB tokens
  4.4 Develop view to show the user how he/she helps the world with its activity
5. Start to gamify the platform
6. Implement footprint carbon calculator and allow the user to pay its impact with the given calculated amount
7. Integrate $URBN on Shapeshift and Uniswapt as $wURBN

