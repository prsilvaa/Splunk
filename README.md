<h1>
    <a href="https://github.com/prsilvaa" target="_blank">
        Splunk Log Analysis
    </a>
</h1>

<h2>Project Objective</h2>
<p>
The objective of this project was to use Splunk to analyse web server logs and extract actionable business and security insights. This included learning SPL (Search Processing Language), performing searches, visualising trends, and identifying anomalies in web access data.
</p>

<h2>Tools Used</h2>
<ul>
    <li>Splunk Enterprise / Splunk Cloud</li>
    <li>SPL (Search Processing Language)</li>
    <li>Apache Web Logs</li>
    <li>Buttercup Dataset</li>
    <li>Charts and dashboards in Splunk</li>
</ul>

<h2>Skills Gained</h2>
<ul>
    <li>Search Processing Language (SPL) for data queries</li>
    <li>Log parsing and analysis</li>
    <li>Extracting client IPs, HTTP status codes, and user agents</li>
    <li>Timeline and transaction analysis</li>
    <li>Identifying successful and failed transactions</li>
    <li>Mapping product IDs to categories</li>
    <li>Building visualisations for business and security insights</li>
</ul>

<h2>Outcome</h2>
<p>
I successfully analysed the Buttercup web server dataset using Splunk. Key achievements included identifying the top client IP addresses, tracking HTTP response codes, mining for specific products and purchases, and visualising user behaviour and browser usage trends. This project enhanced my ability to extract meaningful insights from large datasets and strengthened my skills in log-based security monitoring and business intelligence.
</p>

<div align="center">
    <h3>Failed Requests (Status=404)</h3>
    <img src="get_status_404.png" alt="GET status=404 results" height="80%" width="80%">
    <p>Analysis showing the client IPs generating the most 404 errors.</p>
</div>

<div align="center">
    <h3>All GET Requests</h3>
    <img src="get_requests.png" alt="GET requests results" height="80%" width="80%">
    <p>Mining GET requests to track user activity and product interactions.</p>
</div>

<div align="center">
    <h3>Browser and OS Comparison</h3>
    <img src="browser_os_comparison.png" alt="Browser and OS comparison" height="80%" width="80%">
    <p>Comparison showing the usage trends for Windows vs Mac clients.</p>
</div>
