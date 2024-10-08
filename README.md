# 🐝 **Beehive Project: Data Structures in C for Wildfire Analysis** 🔥

Welcome to the **Beehive Project**! In this exciting data structures project, you'll be analyzing wildfire data in the United States using **C programming**. Think of it as building a **digital beehive**, where each bee (your code) gathers information about wildfires and organizes it in a highly efficient way! 🐝📊 Each function you write will help you analyze large amounts of data, process wildfire information, and produce meaningful results.

Finally, **our aim is to take the honey in this beehive against the angry bees!** 🍯🐝 Your code will face challenges, but with efficient algorithms and smart solutions, you'll gather all the data honey successfully!

---



## 🚩 **Project Context**:
You are provided with a dataset containing records of wildfires 🏞️ that occurred in the United States 🇺🇸 between **1992 and 2015**. This data includes information such as fire size, cause, geographic coordinates (latitude and longitude), and more.

Here is the dataset link:

[1.88 Million US Wildfires Dataset on Kaggle](https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires)

In this project, you will:

1. Analyze the dataset using **C**.
2. Develop custom solutions for location matching.
3. Calculate various fire statistics.
4. Apply **Big O Notation** to analyze the efficiency of your code.

---

### 📝 **Problem Overview**:
Your challenge is to analyze wildfire data and **find the city or state** where each fire occurred, based on **latitude and longitude**. You will also calculate fire statistics like:

- **Percentage of fires by cause** (e.g., human-caused, lightning).
- **Percentage of fire sizes** (e.g., large fires vs small fires).
- **Total percentage of fires** for each city or state relative to the entire dataset.

🌟 **Remember**: You are **NOT** allowed to use any external APIs! This project is all about applying your own solutions using **C programming**.

---

### 🐝 **Your Tasks**:

#### 1. **Input: Process Location Data** 📍
- The dataset contains **geographic coordinates** (latitude and longitude).
- Match these coordinates to specific **cities/states**.
- Develop your own method to find cities based on latitude and longitude. No external libraries or API calls allowed—be creative! 🚀

#### 2. **Percentage of Fires by Cause** 🔥
- For each city/state, calculate the **percentage of wildfires** based on their cause (e.g., human-caused, lightning).
- Sort the causes from **most frequent** to **least frequent**.

#### 3. **Percentage of Fire Sizes** 📏
- For each city/state, calculate the **percentage of wildfires** based on their size, relative to the total size of fires in that city/state.
- Sort fire sizes from **largest to smallest** in terms of percentage.

#### 4. **Calculate Total Fire Percentage** 📊
- Calculate the total percentage of wildfires in each city/state compared to the entire dataset.

#### 5. **Alphabetical Sorting of Cities/States** 🏙️
- Once you process all cities/states, **sort them alphabetically** (A to Z).
- Display:
  1. The **total percentage of wildfires**.
  2. The **sorted list of fire causes** (with percentages).
  3. The **sorted list of fire sizes** (with percentages).

---

### 💡 **What You Will Learn**:
- **Data structure implementation** using C.
- Handling large datasets efficiently.
- Applying **Big O Notation** to evaluate the performance of your algorithms.
- Developing creative solutions without external libraries or APIs.

---

### 🔧 **Requirements**:

1. **📍 Location Matching**: 
   - Create your own algorithm to **match geographic coordinates** (latitude and longitude) to cities/states.
   - **No API calls** allowed!

2. **💻 No Dataset Modifications**: 
   - You **cannot modify the input dataset**. Work with the data as-is.

3. **📈 Algorithm Complexity**:
   - **Analyze the time complexity** of your solution using **Big O notation**.
   - Calculate Big O for location matching, sorting, and percentage calculations.

---

### 🗃️ **Sample Input**:  
You will be provided with:
1. A **dataset file** containing wildfire records (coordinates, sizes, causes, etc.).
2. A text file `cities_states.txt` containing **mixed city and state names**, one per line, like this:
   ```
   California
   Texas
   Los Angeles
   New York
   Miami
   ```

### 🎯 **Example Output**:

For a given city (e.g., California):
```bash
City: California Total: 23% of total fires
Fire Causes (sorted):
1. Human-caused: 50%
2. Lightning: 30%
3. Unknown: 15%
4. Other: 5%

Fire Sizes (sorted):
1. 5000+ acres: 40%
2. 1000-4999 acres: 25%
3. 100-299 acres: 20%
4. 10-99 acres: 10%
5. 0-10 acres: 5%
```

---

### ⚡ **Big O Complexity Analysis**:
You must calculate the time complexity for each function or section of your code:
- **Location Matching**: How efficient is your method for finding cities based on coordinates? Is it O(n), O(log n), or something else?
- **Sorting**: Sorting fire causes and sizes should use algorithms like **quicksort** or **mergesort**, which are O(n log n).
- **Percentage Calculations**: Calculating percentages is generally O(n), where n is the number of records in the dataset.

---

### 🧠 **Beehive Project – A Fun Challenge Awaits!** 🐝

This project isn't just about programming—it's about learning to organize and structure your solutions like a beehive, where each "bee" (your code) plays an important role in the overall success of the system. Keep your code efficient, neat, and buzzing with life! 🌟

---

**Happy coding, and remember: hard work always bears honey! 🍯**
