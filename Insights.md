#  Findings and Insights

In an increasingly saturated beauty market, understanding what customers value—and what they reject—is more essential than ever. This project applies clustering and sentiment analysis to Sephora product and review data to uncover which attributes truly drive customer satisfaction. From ingredient preferences to brand perceptions, our findings provide clear signals for marketing, product development, and strategic positioning. These insights empower brands to align offerings with consumer expectations more effectively.###  Key Insights from the Analysis:

## Customer Sentiment Patterns (Sentiment Analysis)

- Products with **high sentiment polarity (> 0.5)**—such as *Extra Repair Moisture Cream* (Bobbi Brown) and *Revitalizing Supreme+ Creme* (Estée Lauder)—tend to be associated with **hydrating**, **soothing**, and **luxurious-feeling** formulations. These products are not only top-rated but also emotionally appreciated, with strong brand trust and positive word-of-mouth.

- Conversely, products with **negative polarity (< 0)**—like *Mini Must Haves Skincare Set* (Bobbi Brown) or *NuBODY – Body Toning Device* (NuFACE)—often reflect **unmet expectations**, **performance doubts**, or **pricing concerns**. Despite high “loves_count” or brand prestige, sentiment reveals a deeper layer of dissatisfaction.

- **Polarity analysis provides a more nuanced view** than star ratings alone, uncovering emotional reactions that guide customer loyalty or churn.

- The gap between high and low performers emphasizes the need for **clear product claims**, **realistic expectations**, and **customer education**, especially for high-investment or treatment-oriented products.



## 🧠 Clustering – Insights

- Using K-Means clustering (k=6), products were segmented based on **price**, **sale value**, **ratings**, **review count**, and **popularity (loves_count)**, revealing **distinct product groups** across Sephora’s catalog.

### Key Cluster Characteristics:

- **Cluster 0: High Rating, Low Price**  
  - Budget-friendly products with very high customer ratings (4.5–5.0)  
  - Represents Sephora’s best-performing value segment—ideal for price-sensitive but quality-conscious consumers.

- **Cluster 1: High Price, Unstable Rating**  
  - Premium or luxury products priced above $300, but with widely varying ratings (1.0–5.0)  
  - Indicates that higher price does not always guarantee satisfaction; may require repositioning or clearer value communication.

- **Cluster 2: Affordable with Mixed Feedback**  
  - Mid- to low-priced products (< $100) with highly variable ratings  
  - May benefit from better review management or customer education.

- **Cluster 3: Mixed Ratings at Broad Price Range**  
  - Wide price range (up to $250), but inconsistent user experience  
  - Suggests that customer satisfaction may depend more on formulation than price alone.

- **Cluster 4: Low Price, Moderate Rating**  
  - Lower-priced items with average ratings (~3.0–4.0)  
  - Functional products with room for improvement or better targeting.

- **Cluster 5: Mid Price, High Rating**  
  - Well-balanced products priced around $100–$200 with strong positive ratings  
  - A potential sweet spot for marketing focus—combining accessibility and quality.



## Ingredient-Driven Preferences (Ingredient Analysis)

### Ingredients with High Emotional Impact(Intensity)

  - Ingredients such as **callicarpa japonica fruit extract** and **oryza sativa (rice) powder** exhibit **both high polarity and high emotional intensity**, indicating that they strongly resonate with users and are associated with **positive emotional experiences**.
  - Though not the most common, these ingredients have the potential to become **hero ingredients** in marketing, as they evoke strong reactions even with limited appearances.

### Positive & Negative Sentiment Ingredients(Polarity)

- **Positively Associated Ingredients**:
  - *Fragrance*, *squalane*, *sodium PCA*, *propanediol*, and *fragrance compound* frequently appear in high-polarity products.
  - These contribute to hydration, smooth texture, and pleasant sensory experience—factors that drive customer satisfaction.

- **Negatively Associated Ingredients**:
  - *Phenoxyethanol*, *dimethicone*, *caffeine*, *sodium hydroxide*, *silica*, and *butylene glycol* are more common in low-polarity products.
  - While these serve important functional roles, they may trigger negative sentiment due to concerns over irritation, harshness, or synthetic formulation.

- Ingredients like **butylene glycol**, appearing in both high- and low-polarity products, highlight the importance of **contextual formulation and target audience sensitivity**.

### Ingredient Signals by Pricing Tier

- **High-Priced Products**:
  - Frequently feature *vitamin E*, *dimethicone*, *butylene glycol*, *xanthan gum*, *EDTA*, and *hyaluronic acid*—ingredients aligned with **hydration, stability, and luxury perception**.
  - These ingredients contribute to the sensory richness and clinical feel expected in premium skincare.

- **Low-Priced Products**:
  - Contain more *1,2-hexanediol*, *hydroxyacetophenone*, *propylene glycol*, *sodium chloride*, and *allantoin*—chosen for **cost-effectiveness, stability, and functional simplicity**.
  - May be perceived as less premium despite efficacy, underscoring the need for **clear communication** of value and performance.


 These insights demonstrate that ingredient choice not only affects product performance, but also shapes consumer perception, emotional resonance, and perceived value. By understanding how ingredients vary across emotional intensity, sentiment polarity, and pricing tiers, brands can make more informed decisions in formulation, positioning, and communication strategies to align with customer expectations and market demands.
