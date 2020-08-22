<h2>Data Lakes: CSV flat files -> Python -> Tableau -> Server -> Business Analysis -> New data coming in --> CSV fieles and so on..</h2>
<h3>Intro</h3>
<img src="images/datapipeline.jpg">
<ul>
  <li>CSV as dasta extracts from different systems.</li>
  <li>Python for ETL (extract, transform, load).</li>
  <li>Tableau for data visualization dasboards.</li>
  <li>Server to get dasboard published for stakeholders.</li>
</ul>
<h3>Demo with conclusions</h3>
<ul>
  <li>Python script combines flat files into one Tableau input.</li>
  <li>In this case I use static source  which is CSV flat files <b>(batch processing)</b>.</li>
  <li>However data pipelines are built also for real-time sources where target system requires constant data update <b>(stream processing)</b>.</li>
  <li>The example shows that ultimate destination of data pipelines doesn't have to be a data warehouse.</li>
  <li>Data pipeline can route the processed data into another applications like Tableu for building dashboards.</li>
  <li>Once dashboard built, there is the Tableau option for sending it into server.</li>
</ul>

<h3>Tableau Dashboard</h3>
<img src="images/dashboard.JPG">
