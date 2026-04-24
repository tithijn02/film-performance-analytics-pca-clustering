# 🎬 Movie Success Segmentation using PCA & Clustering

Understanding what drives a movie’s success is not straightforward — this project explores how audience engagement, critical reception, and revenue interact to shape different types of successful films.

---

## 🚨 The Problem

Film success is often evaluated using isolated metrics like ratings or revenue, but this fragmented view fails to capture the underlying patterns that differentiate blockbuster hits, critically acclaimed films, and niche productions.

This creates challenges for:
- production teams deciding content strategy  
- marketers targeting the right audience  
- studios balancing commercial success with critical appeal  

---

## 💡 The Solution

This project applies dimensionality reduction and clustering techniques to uncover hidden structures within movie performance data. By transforming multiple variables into meaningful components and grouping similar films together, it provides a clearer understanding of how different success profiles emerge.

The analysis reveals distinct segments such as blockbuster-driven films, critically acclaimed productions, and commercially successful franchise-based content, offering a more structured way to interpret performance.

---

## 📊 Business Impact

The insights enable a more strategic approach to decision-making in the film industry by identifying what drives different types of success.

This can support:
- better investment decisions in film production  
- targeted marketing strategies for different audience segments  
- improved positioning of films based on expected performance profiles  

---

## 🛠️ How it was done

The analysis was conducted on a dataset of top-rated IMDb movies using key numerical features such as runtime, ratings, votes, and revenue. Principal Component Analysis (PCA) was applied to reduce dimensionality, with the first two components capturing over 70% of the variance, revealing strong relationships between variables :contentReference[oaicite:0]{index=0}.

Clustering techniques (K-means and hierarchical clustering) were then used to identify distinct movie segments. The results showed clear groupings such as high-revenue blockbusters, critically acclaimed films with moderate revenue, and niche or independent productions with limited exposure.

These findings were validated through multiple methods, ensuring robust and interpretable segmentation.

---

## 📄 Full Case Study

👉 [View Report](./Report.pdf)
