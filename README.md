# datax-labs-task1
<h2>🧹 Data Cleaning Summary</h2>

<ul>
  <li><strong>Step 1:</strong> Formatted column headers in lowercase and replaced space with hyphen.</li>
  <li><strong>Step 2:</strong> Replaced gender values (<em>M/F</em>) with full forms (<em>Male/Female</em>) and replaced empty value with <code>null</code>.</li>
  <li><strong>Step 3:</strong> Removed duplicate rows to ensure unique records.</li>
  <li><strong>Step 4:</strong> Trimmed and capitalized customer names for consistency.</li>
  <li><strong>Step 5:</strong> Standardized date formats into <code>dd-mm-yyyy</code>.</li>
  <li><strong>Step 6:</strong> Changed data type of date column from text to date after ensuring there is no loss of any value</li>
  <li><strong>Step 7:</strong> Converted age column into whole numbers (handling text like "Thirty-five").</li>
  <li><strong>Step 8:</strong> Cleaned hidden characters and extra spaces using <code>Text.Clean</code> + <code>Text.Trim</code>.</li>
  <li><strong>Step 9:</strong> Ensured null values were properly handled and replaced where necessary.</li>
</ul>

<p><em>All transformations were performed in Power Query M to maintain data integrity and prepare the dataset for analysis.</em></p>
