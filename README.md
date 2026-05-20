import streamlit as st

# Page config
st.set_page_config(page_title="Piyush Portfolio", page_icon="🚀", layout="wide")




# ---------------- HEADER ----------------
st.title("Piyush Pandey")
st.subheader("Data Analyst/ Scientist")

st.write("📧 piyushpandeyy18@gmail.com | 🔗 www.linkedin.com/in/piyush-pandey-9abb8b2a4| 💻 https://github.com/Techtics64")

st.markdown("---")

# ---------------- PROFESSIONAL SUMMARY ----------------
st.header("🧠 Professional Summary")
st.write("""
Aspiring Data Scientist with a strong foundation in Python, including libraries such as NumPy, Pandas, and Matplotlib for data analysis 
and visualization. Proficient in working with SQL for data querying and experienced in using Excel and Power BI for data handling and dashboard 
creation. Familiar with fundamental machine learning models and their practical applications in solving real-world problems. Possesses a
solid understanding of programming concepts, data structures, and analytical thinking. Continuously learning and applying new techniques through
hands-on projects. Additionally, experienced in building simple interactive applications using Streamlit.
""")

# ---------------- EXPERIENCE ----------------
st.header("💼 Experience")
st.subheader("""1. Public Works Department, Uttar Pradesh – Data Science Intern (June 2025 – Aug 2025)""")
st.write("""
- Processed and analyzed large-scale road infrastructure data across 70+ districts using Python
(Pandas, NumPy) (Situation/Task), performing data cleaning, transformation, and validation 
(Action), resulting in improved data accuracy and consistency for official reporting (Result).

- Generated statistical insights and built data visualizations using Power BI and Excel 
(Action) to support road planning and maintenance strategies (Task), enabling data-driven 
decision-making by senior engineers and officials (Result).

- Designed interactive dashboards in Power BI featuring key metrics such as regional distribution,
infrastructure trends, and performance indicators (Action), enhancing data interpretation and 
reporting efficiency (Result).

- Collaborated with cross-functional teams and department staff (Action) to identify data 
inconsistencies and implement corrective measures (Task), ensuring high data integrity and
reliable analytical outputs (Result).

""")

st.subheader("""2. Skillrisers Infotech Pvt. Ltd. – Data Analyst Intern""")
st.write("""
• Gained hands-on experience in data analytics fundamentals (Situation), focusing on Python, 
data cleaning, data visualization, and MS Excel (Task), by working on practical assignments 
and real-world datasets (Action), strengthening core analytical and problem-solving skills 
(Result).

• Developed a Face Recognition System using Python (Action), applying concepts of image processing
and machine learning (Task), demonstrating the ability to build end-to-end data-driven solutions
(Result).
""")

# ---------------- PROJECTS ----------------
st.header("🚀 Projects")

st.subheader("1. Churn Rate Predicition Application")
st.write("""
- Built an end-to-end churn prediction system to identify high-risk customers using behavioral and demographic 
data.  
- Performed in-depth exploratory data analysis and engineered meaningful features to capture customer usage 
patterns. 
- Delivered explainable churn insights to support proactive, data-driven customer retention strategies. 
- Technologies Used: Python(Numpy, Pandas, Streamlit, Seaborn), Scikit-Learn, Kaggle, EDA | Accuracy 72% 
""")

st.subheader("2. HR Dashboard using Power BI")
st.write("""
- Developed an interactive HR analytics dashboard in Power BI to analyze employee attrition 
trends, enabling data-driven decision making.
-  key metrics such as attrition rate, department-wise turnover, job roles, age groups, and
salary insights using dynamic charts and filters.
- Identified patterns and factors influencing employee attrition, helping in improving retention
strategies and workforce planning.
- Technologies Used: Power BI, Kaggle.
- st.image("https://tinyurl.com/2s3x6br7")
""")

st.subheader("2. Used Car Prediction Application")
st.write("""
- Built a machine learning model to predict used car prices using vehicle and ownership features. 
- Cleaned and analyzed data to identify key factors influencing price variations. 
- Trained and evaluated regression models to generate reliable price predictions.
- Technologies Used: Python(Numpy,Pandas,Matplotlib), Scikit-Learn, Kaggle, Streamlit | Accuracy 67% 
""")

# ---------------- SKILLS ----------------
st.header("💻 Skills")

col1, col2, col3 = st.columns(3)

with col1:
    st.subheader("Technical")
    st.write("- Python")
    st.write("- Java")
    st.write("- MySQL")
    st.write("- MS Excel")
    st.write("- Power BI")
    st.write("- ML(Scikit Learn)")
    st.write("- Streamlit")

with col2:
    st.subheader("Tools")
    st.write("- VS Code")
    st.write("- Git")
    st.write("- Kaggle")
    st.write("- Jupyter")

with col3:
    st.subheader("Core CS Concepts")
    st.write("- Operating System")
    st.write("- OOP Concepts")
    st.write("- Computer Network")
    st.write("- Data Structures")
    st.write("- Database Management System")
    

# ---------------- EDUCATION ----------------
st.header("🎓 Education")
st.markdown("""
**St. Patrick's Sr. Sec. School, Jaunpur**""") 
st.write("10th(2019)-12th(2021)")

st.markdown("""
**IMS Engineering College, Ghaziabad**

B.Tech(IT)(2022-26)
""")

# ---------------- FOOTER ----------------
st.markdown("---")

st.write("© 2026 Piyush Pandey")
