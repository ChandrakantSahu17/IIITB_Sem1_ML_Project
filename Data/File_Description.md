<h2>File Description:</h2>
<p>This is a relational dataset from two systems. Each file is prefaced with the source (either air_ or hpg_) to indicate its origin. Each restaurant has a unique <code>chw_store_id</code> and <code>yom_store_id</code>. Note that not all restaurants are covered by both systems, and that you have been provided data beyond the restaurants for which you must forecast.</p>
<h2><strong>train.csv</strong></h2>
<p>This file contains historical visit data for the chwiggy restaurants.</p>
<ol>
<li>chw_store_id - store id with air prefix.</li>
<li>visit_date - the date</li>
<li>visitors - the number of visitors to the restaurant on the date</li>
</ol>
<h2><strong>sample_submission.csv</strong></h2>
<p>This file shows a submission in the correct format, including the days for which you must forecast.</p>
<ol>
<li>id - the id is formed by concatenating the chw_store_id and visit_date with an underscore.</li>
<li>visitors- the number of visitors forecasted for the store and date combination.</li>
</ol>
<h2><strong>MetaData</strong></h2>
<p>There are 6 files in metadata, the column names are self explanatory. You may use this information to improve your predictions.</p>
