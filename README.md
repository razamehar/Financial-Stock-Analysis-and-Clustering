# Financial-Stock-Analysis-and-Clustering
In a thorough analysis of 157 US Energy stocks throughout January to December '23, I employed advanced clustering techniques, including KMeans, Hierarchical, and Spectral Clustering, to identify bullish and bearish trends. The clustering methodology revealed overbought and overpriced stocks, profitable investments, and stocks facing losses. Additionally, a focus on volatility analysis pinpointed the most volatile stocks in the dataset. This comprehensive approach enables investors to make informed decisions and manage risks effectively. Furthermore, seamless integration with Kafka ensures real-time updates and subscriptions for stakeholders, enhancing accessibility to critical market insights.

## Project Overview
This project involves analyzing 157 US-based Energy sector stocks from January to December 2023. 

### Analysis Steps
1. **Data Distribution Analysis:**
   - Analyzing the distribution of data for insights into stock performance.

2. **Feature Engineering:**
   - Enhancing data features to improve the accuracy of subsequent analyses.

3. **Technical Indicators:**
   - Employing technical indicators to evaluate stocks as Bullish, Bearish, or Overbought/Oversold.

4. **Risk Analysis:**
   - Categorizing stocks as Profitable, Unprofitable, or Volatile.

### Clustering Techniques
Utilizing clustering techniques like KMeans, Agglomerative Hierarchical, and Spectral Clustering to identify distinct groups among the analyzed stocks.

### Findings
The analysis reveals a common theme among energy sector stocks, offering a balance of medium to high returns with relatively low volatility.

### Integration with Kafka
The processed data is seamlessly integrated with Kafka, enabling subscription by other systems for further analysis.

## Usage
### Prerequisites
- Python 3.10.12
- Required Python packages:
  - kafka-python
  - yfinance
  - pyspark
  - TA-Lib

### Environment Setup
1. Install the required libraries using the following commands:

   ```bash
   pip install kafka-python
   pip install yfinance --upgrade --no-cache-dir
   pip install pyspark
   pip install TA-Lib

2. Download and instal TA-Lib using the following instructions:
   ```bash
   wget http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-src.tar.gz
   tar -xzvf ta-lib-0.4.0-src.tar.gz
   cd ta-lib/
   ./configure --prefix=/usr
   make
   make install
   cd /content
   
## License
This project is licensed under the Raza Mehar License. See the [LICENSE.md](LICENSE.md) file for details.

## Contact
For any questions or clarifications, please contact Raza Mehar at [raza.mehar@gmail.com].
