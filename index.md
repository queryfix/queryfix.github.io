---
layout: page
---




<p class="header">
  Query Explanations
</p>
<p class="header">
<small>Forget about data explanation!  <br/>Get to the root cause using query explanation.  </small>
</p>
<p class="header">
  <img width="400" src="{{ site.url }}/files/images/qfix.png" style="margin-left: auto; margin-right: auto;"/>
</p>





Traditional database cleaning and explanation research has focused on techniques such as
anomaly/outlier detection, dimensionality reduction, data summarization, 
predicate synthesis, ETL, and others, as ways to prevent, detect, or resolve (clean) data errors.

However, these _data oriented_ approaches ignore a key vector of data errors -- **queries**!
The majority of user facing systems -- billing, HR, customer service, web application -- generate
queries based on user submissions.  Can we use the sequence of past queries from the transaction log
to both find _and repair_ incorrect errors due to user slip-ups?

QFix is a fundamentally novel approach towards getting to the root cause of errors in your database.
Instead of describing data errors by examining data in the database,
explains and fixes data errors by analyzing your past _queries_ and suggests ways to 
repair the incorrect queries that it finds.

## Personnel

* Xiaolan Wang (PhD Student)
* Alexandra Meliou (PI)
* Eugene Wu (PI)


# Publications

<div class="section" id="publications">

<div class="item">
  <div class="screenshot"><img src="{{ site.url }}/files/images/qfix_arxiv_paper.png" width="200"/></div>
  <div class="text">
    <div class="title">
      <a href="{{ site.url }}/files/papers/qfix-sigmod17.pdf">
        QFix: Diagnosing errors through query histories
      </a>
    </div>
    <div class="authors">Xiaolan Wang, Alexandra Meliou, Eugene Wu</div>
    <div class="links">
      <span class="conf">SIGMOD 17</span>
    </div>
  </div>
  <div style="clear: both"></div>
</div>



<div class="item">
  <div class="screenshot"><img src="{{ site.url }}/files/images/preview_qfix-sigmod16.png" width="200"/></div>
  <div class="text">
    <div class="title">
      <a href="{{ site.url }}/files/papers/qfix-sigmod16.pdf">
        QFix: Demonstrating error diagnosis in query histories
      </a>
    </div>
    <div class="authors">Xiaolan Wang, Alexandra Meliou, Eugene Wu</div>
    <div class="links">
      <span class="conf">SIGMOD 2016 Demo</span>
    </div>
  </div>
  <div style="clear: both"></div>
</div>




