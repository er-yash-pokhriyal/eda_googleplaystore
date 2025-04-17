## Exploratory Data Analysis (EDA) - Hinglish Explanation

![EDA](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.linkedin.com%2Fpulse%2Fpreparing-data-eda-mahsa-salimi-2859f&psig=AOvVaw1AykEz-WSUyR8eVvX8_O9X&ust=1744996467879000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCPjjo8fI34wDFQAAAAAdAAAAABAJ)

**EDA Kya hai (What is EDA?)**

EDA basically data ko "explore" karne ka process hai. Matlab, data mein kya chhupa hua hai, woh pata karna. Isme hum data ke patterns, trends, relationships, aur kuch ajeeb cheezo (anomalies) ko dhoondte hain. EDA ka main goal hota hai data ke baare mein ek "feel" develop karna, taki hum aage ke analysis aur modelling ke liye ready ho sakein.

**EDA ke Steps (Steps of EDA):**

1.  **Data Collection:** Sabse pehle, data jama karte hain. Jaise, CSV file se, database se, ya API se.
2.  **Data Cleaning:** Data mein aksar "missing values" (khaali jagah), "duplicates" (do baar repeat hone wale values), aur "outliers" (bahut alag values ) hote hain. In sabko "clean" karna zaroori hai.
3.  **Data Exploration:** Yahan hum data ko "visualize" karte hain aur "summarize" karte hain.
    * **Summary Statistics:** Jaise, mean, median, mode, aur standard deviation. Yeh humein data ke "central tendency" aur "spread" ke baare mein batate hain.
    * **Visualizations:**
        * **Histograms:** Data ka distribution dikhate hain.
        * **Scatter plots:** Do variables ke beech ka relationship dikhate hain.
        * **Box plots:** Data ke quartiles aur outliers dikhate hain.
        * **Bar charts:** Categorical data dikhate hain.
4.  **Pattern Identification:** Visualization aur summary statistics se hum patterns aur trends dhoondte hain. Jaise, koi correlation hai kya? Koi outliers hain kya?
5.  **Hypothesis Generation:** EDA ke results ke basis par, hum "hypotheses" banate hain, jo aage ke analysis ke liye useful hote hain.

**Example: Sales Data ka EDA (Example of Sales Data EDA)**

Maan lo, humare paas ek company ka sales data hai, jismein product name, sales amount, aur date hai. Hum EDA karke yeh jaanna chahte hain ki:

* Kis product ki sales sabse zyada hai?
* Kya sales mein koi seasonal trends hain? (Jaise, holidays ke time sales badhti hain kya?)
* Kya sales aur date ke beech koi correlation hai?
* Kya sales data mein koi outliers hain?

**Steps:**

1.  **Data Import:** Hum CSV file ko Python mein pandas library ka use karke import karte hain.
2.  **Data Cleaning:** Hum missing values ko handle karte hain aur duplicate rows ko remove karte hain.
3.  **Data Exploration:**
    * Hum `sales_amount` ka histogram banate hain, yeh dekhne ke liye ki sales ka distribution kaisa hai.
    * Hum `product_name` ke liye bar chart banate hain, yeh dekhne ke liye ki kis product ki sales sabse zyada hai.
    * Hum `date` aur `sales_amount` ka scatter plot banate hain, yeh dekhne ke liye ki koi trend hai kya.
    * Hum `sales_amount` ke liye box plot banate hain, outliers dekhne ke liye.
4.  **Pattern Identification:**
    * Bar chart se, hum dekhte hain ki product "X" ki sales sabse zyada hai.
    * Scatter plot se, hum dekhte hain ki holidays ke time sales badhti hain.
    * Box plot se, hum kuch outliers detect karte hain, jo shayad data entry errors hain.
5.  **Hypothesis Generation:**
    * "Product X" ko zyada promote karna chahiye.
    * Holidays ke time inventory increase karni chahiye.
    * Outliers ko investigate karna chahiye.

Basically, EDA humein data ko better samajhne mein help karta hai aur aage ke analysis ke liye valuable insights deta hai.
