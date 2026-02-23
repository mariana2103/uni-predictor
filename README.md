
## 🎓 Admission Predictor PT: Hacking the Education "Market"

### "Treating university placements as a high-stakes behavioral data puzzle."

**The "Why" (Motivation)**
I’ve always been fascinated by how thousands of individual choices converge into a single, predictable number: the "Nota do Último Colocado." Looking at the Portuguese national application process, I didn't just see students and grades; I saw a massive, chaotic data set waiting to be solved. I wanted to apply a strategic "game sense" to data—translating the messy psychological shifts of thousands of applicants into a logical, weighted model. This isn't just about grades; it's about understanding the mechanics of demand and how thousands of independent variables settle into a final equilibrium.

**Project Goals**

* **The Trend Hunter**: Identifying the "hidden gems" and the "overhyped bubbles" in the academic market before the final numbers are out.
* **The Chaos Organizer**: Wrangling years of fragmented public data into one beautiful, clean SQL database—because messy data is the ultimate opponent.
* **Pattern Recognition**: Analyzing how a shift in one exam's difficulty creates a ripple effect across dozens of unrelated courses.

**Technical Stack**

* **Python (The Engine)**: Using Pandas and NumPy to clean and transform the raw public data.
* **SQL (The Library)**: Storing everything in a relational structure to track how institutions evolve over time.
* **Scikit-Learn (The Brain)**: Powering the regression models that attempt to map out the next placement cycle.
* **Matplotlib (The Artist)**: Visualizing the "heat" of the market to see where the competition is actually peaking.

**The "How" (The Data Pipeline)**

* **Step 1: The Cleanup**: I harvested data from public sources like Infocursos and DGES. Dealing with university mergers and renamed courses was like solving a multi-year puzzle, requiring serious ETL (Extract, Transform, Load) logic.
* **Step 2: Smart Metrics**: I developed a **Demand Ratio** (applicants vs. seats) and factored in **Exam Volatility**. It’s about understanding the "currency" of the year—some years, a 15 is worth more than a 16 in others.
* **Step 3: The Prediction Logic**: I applied weighted regression models. It’s a mathematical attempt to find the equilibrium point where supply meets the frantic demand of the application season.

**What’s Next? (The Accuracy Challenge)**
The real thrill is seeing if the math holds up against reality. In the next phase, I'm diving deep into the "Validation Lab":

* **Backtesting**: I’ll be running the model on 2022 and 2023 data to see if it would have "guessed" the 2024 results. It’s the ultimate stress test for my logic.
* **Error Analysis (MAE)**: I’ll be tracking the Mean Absolute Error to see exactly where the model gets "surprised" by human behavior.
* **The "Blind" Test**: Once the next cycle hits, I’ll compare my data-driven predictions against the official results to see how well a Python script can outsmart the chaos of human choice.

**Impact & Insights**
By calculating a **Stability Score** for each course, this project reveals the "personality" of different academic fields. Some are steady as a rock; others are as volatile as a tech stock. It’s an exploration of how data can map out human intention, one decimal point at a time.
