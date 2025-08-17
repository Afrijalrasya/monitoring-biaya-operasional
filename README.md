# 🚀 Operational Cost Monitoring - ETL & Dashboard

This project aims to build an ETL (Extract, Transform, Load) process and an interactive dashboard to monitor the company's cost usage by department and category in 2025. The project is developed using Pentaho Data Integration (PDI) for ETL process and Power BI for data visualization.


🔄 Alur ETL
![ETL Flow](docs/proses_etl.png)


# Dashboard
![Dashboard](docs/Monitoring_dashboard.png)

# 📁 Struktur Folder

    .
    ├── docs/                        
    │   ├── Dashboard-PBI.png        # Power BI dashboard view
    │   ├── model-data.pdf           # Diagram model data
    │   └── proses_etl.png           # ETL flowchart
    ├── kettle/                      # Folder berisi file Kettle (ETL)
    │   ├── Etl_monitoring_biaya.kjb # Main job of ETL
    │   ├── job/                     
    │   ├── setVariable_timestamp.ktr
    │   ├── setbudget.ktr
    │   ├── staging_area.ktr
    │   ├── transaksi_load.ktr
    │   └── transform.ktr
    ├── LICENSE
    └── README.md



# 📁 Data Source

    Budget: Derived from Excel file containing budget allocation per department and category.
    
    Cost Transaction : Dummy transaction data.
    
    Supporting Dimensions : Reference tables for dim_time, dim_category, dim_department.


## About Me

Hello, I am **Afrijal Rasya Putra**, an Informatics student who is interested in exploring the world of **Data**. Although it's still early in my college journey, I'm excited to learn about how data is processed and turned into meaningful information.

📌 I am currently studying:
- Data processing techniques
- **SQL** and the basics of data manipulation
- Basic concepts of **ETL** and data pipeline workflows

I love learning and exploring new things, especially those related to data. I am currently building my skills gradually and constantly looking for opportunities to grow. I am also open to **internships** or **collaborative projects** that can give me hands-on experience and help my learning process.

📫 Feel free to connect or discuss-I'd love to learn and grow together!


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/afrijalrasyaputra/)
    
